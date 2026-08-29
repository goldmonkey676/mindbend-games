# Mindbend — public repo

This is the **public** repo for Mindbend. It is served by GitHub Pages at
https://goldmonkey676.github.io/mindbend-games/

## What lives here

Only the things students load in their browser:

- `games/` — finished, playable game HTML files (each self-contained, no build step)
- `class.html` — the page a student opens to see their class's games; reads
  `?id=<class-id>` and fetches `classes/<id>.json`
- `classes/*.json` — one file per class: its name and its list of games
  (authored **newest-first**, so this week's game is at the top)

## What must NEVER be here

Source material, drafts, project notes, and the design spec live in a
**separate private repo (`mindbend`)**. Never copy any of that into this repo —
not notes, not spec files, not work-in-progress games.

## Editing games

Games are built in the private repo and **copied here to publish**. Don't edit
game files in this repo — change them in the private repo and re-copy, or the
two copies will drift apart.
