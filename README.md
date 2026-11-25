# FEN Library — GitHub Pages site

Static export of the FEN Library chess teaching app.

## What this is

- `index.html` is a single self-contained page with the position library embedded in it — no server or database needed.
- Search, and filter by folder, difficulty, phase (Opening / Middlegame / Endgame), opening name, and side to move (White to move / Black to move).
- Tap “Show / hide solution” on a card to reveal its solution.

## Current content

As of 25 Nov 2026, the library exported here is empty — 0 positions, 0 folders.
Add positions in the FEN Library app in Muse first, then re-export.

## How to update it

1. Open the FEN Library app in Muse.
2. Add folders and positions (FEN / PGN, difficulty 1–5, phase, opening name, notes, solution).
3. In the app, open Import / Export → “GitHub Pages site (index.html)” and download it.
4. Replace `index.html` in this repo with the new file and commit.
5. GitHub Pages will rebuild from the branch you selected in Settings → Pages.

## How to enable Pages

Settings → Pages → Build and deployment → Source: Deploy from a branch →
Branch: `main`, Folder: `/ (root)`.

Note: on GitHub Free, Pages requires a public repository. On Pro / Team /
Enterprise, Pages can be published from a private repository — but the
published site itself is still public on the internet.

## What this is not

The full cloud app (with Neon database, saving across devices, and the
Lichess cloud engine panel) lives in Muse. This repo is only the static,
read-only Pages export. Do not put database credentials or other secrets
in this repo.
