# Vacuum Racer

A 3D racing game in the browser. Pick Dave, Rosie or Dasz, race across three tracks (Dusty Dunes, Canyon Twist and Scrapyard Night), suck up the balls, boost into rivals to make them spill, and fly over ramps.

## Play

- **Computer:** W A S D or the arrow keys to drive, Space to vacuum, Shift or E to boost, P to pause, M to mute, R to restart.
- **Phone or tablet:** use the on-screen buttons. Landscape works best.
- **Install it:** open the game in Chrome or Safari and choose "Add to Home Screen" or "Install app". After the first visit it also works offline.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The game |
| `three.min.js` | three.js r128, the 3D library (MIT licence, see `LICENSE-three.txt`) |
| `sw.js` | Lets the game work offline after the first visit |
| `manifest.webmanifest`, `icon*.png`, `icon.svg`, `apple-touch-icon.png` | App name and icons for installing on a phone |
| `.nojekyll` | Tells GitHub Pages to publish the files exactly as they are |

## Updating the game

Upload the new `index.html`, then open `sw.js` and change `vacuum-racer-v1` to `vacuum-racer-v2` (and so on). That tells players' browsers to fetch the new version.

Game design and characters by Dasz. 3D graphics: three.js, © 2010–2021 three.js authors, MIT licence.
