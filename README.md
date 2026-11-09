# Perk Ledger

A personal PWA for tracking credit card benefits: credits used per period, how much of the annual fee you've earned back, points balance, and earning rates. Starts with the Amex Gold; more cards can be added in the app.

- No accounts and no server. All data is stored in the browser on your phone (localStorage).
- Works offline once installed (service worker in `sw.js`).
- **Save backup** exports a JSON file; **Restore from backup** imports it.

## Install
Open the GitHub Pages URL in Chrome on Android → menu → **Install app** / **Add to Home screen**.

## Files
- `index.html` – the whole app (HTML, CSS, JS)
- `manifest.webmanifest` – install metadata and icons
- `sw.js` – offline cache. Bump `VERSION` when changing app files.
- `icons/` – app icons
