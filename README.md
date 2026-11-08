# Number Stacks

A single-page stacking game inspired by "number block tower" videos: every block is a bigger
number — One, Ten, … One Million, One Billion, Quadrillion, Centillion, Millinillion,
Micrillion, Googolplex, and on into power towers and up-arrow notation.

Tap / click / press Space to drop the sliding block onto the tower. Any part that hangs over the
edge is sliced off, so the tower narrows as you go. Land within a few pixels of the block below for a
**Perfect** drop; three or more in a row widen the block back out. Milestone blocks also get
"fact cards" beside them (10!, the 32‑bit integer limit, Googol, 100!, the largest known prime, …).

## Speeds

- **🐢 Slow (little kids):** about a third of normal speed, barely speeds up, wider blocks, a bigger
  window for Perfect drops, and 3 hearts, so a complete miss costs a heart instead of ending the game.
- **🙂 Normal:** the classic game.
- **🔥 Fast:** quicker start and a higher top speed.

The game remembers the chosen speed, and each speed keeps its own best score.

## Play locally

Open `index.html` in a browser. It has no build step or dependencies.

## Host on GitHub Pages

1. Push this repo to GitHub.
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch**, then choose `main` / `(root)`.
3. The game is served at `https://<user>.github.io/<repo>/`.
