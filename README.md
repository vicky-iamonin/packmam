# Chomp Arcade

A Pac-Man-style maze chase game built as a single self-contained `index.html` file — no build step, no dependencies beyond a Google Fonts stylesheet.

## Play it

Open `index.html` in a browser, or enable GitHub Pages for this repo (Settings → Pages → deploy from `main` / root) and play it straight from the web.

## Features

- Three difficulty levels — **Easy**, **Medium**, **Hard** — each with its own ghost count, ghost speed, and lives
- **1×/2×/3× speed toggle** to fast-forward the whole game
- Power pellets, frightened/eaten ghost states, and combo scoring
- Keyboard (arrow keys / WASD, `P` to pause) and on-screen D-pad controls for touch
- Local high score saved in the browser

## Tech

Plain HTML, CSS, and vanilla JavaScript rendering to a `<canvas>`. No frameworks, no bundler.
