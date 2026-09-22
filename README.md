# Neon Velocity — 3D Synthwave Racer

A single-file 3D endless racer built with Three.js. Outrun the grid, dodge walls,
jump barriers, blast crates and chain orbs for combos.

This repository is a mirror of a game originally published on Arena's Code Arena.
It is a **self-contained** `index.html`: no build step, no external dependencies,
no asset downloads. Open the file directly in any modern browser, or serve it
from GitHub Pages.

## Play locally

Just open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## GitHub Pages

Enable Pages with the source set to the repository root (`main` branch). The game
will be served at `https://<user>.github.io/neon-velocity/`.

## Controls

| Action | Keys |
| --- | --- |
| Switch lane | `←` / `→` or `A` / `D` |
| Jump | `↑` / `W` / `Space` |
| Pause | `P` / `Esc` |
| Sound | `M` |

Touch: swipe left/right to change lanes, tap the top of the screen to jump.

## Notes

- The gameplay bundle (Three.js + game code) is inlined into `index.html`.
- `index.html` here is the standalone build served by the game's `index.html`
  route, which is the full playable game (the site's `/` route is an Arena
  wrapper page).
