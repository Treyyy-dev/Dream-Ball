# Dream Ball

A 3D basketball game you can install on your phone. Build a squad, open player, shoe and skill-card packs, set a lineup and a 10-card dribble-move deck, and play a story-mode season with Pass, Shoot (hold and release on green) and stamina-powered move cards.

## Play

Open the GitHub Pages link for this repo on your phone, then:

- **Android (Chrome):** tap **Install** in the top bar, or use the menu's "Add to Home screen".
- **iPhone (Safari):** tap Share, then "Add to Home Screen".

After the first load it works offline. Progress saves on the device.

## Files

- `index.html` — the whole game
- `manifest.webmanifest` — app name, icons and portrait lock
- `sw.js` — service worker for offline play
- `icons/` — home-screen icons

When you change `index.html`, bump `VERSION` in `sw.js` so installed copies pick up the update.
