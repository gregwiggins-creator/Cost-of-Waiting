# Cost of Waiting — Northstar (phone app)

A self-contained web app (PWA). No App Store, no accounts, works offline once loaded.
All the files in this folder are the app.

## Files
- `index.html` — the app (everything is inside this one file)
- `manifest.webmanifest` — makes it installable with the Northstar icon
- `service-worker.js` — lets it run offline
- `icon-*.png`, `favicon-32.png` — app icons

## Get it on your phone (recommended: host it)
The app works fully — installable + offline — when served from a web address (https).

1. Put this folder on any static host: Vercel, Netlify, GitHub Pages, or your own site.
   (On Vercel/Netlify you can literally drag-and-drop the folder.)
2. Open the resulting link on your phone.
3. Install it:
   - **iPhone (Safari):** tap **Share** → **Add to Home Screen** → **Add**.
   - **Android (Chrome):** tap the **Install** button in the app, or the **⋮** menu → **Install app**.
4. It now lives on your home screen with the gold-star icon and opens full-screen.

## Quick test on a computer
Open a terminal in this folder and run:
```
python3 -m http.server 8000
```
Then visit `http://localhost:8000`. (Serving it this way — rather than double-clicking
the file — is what enables the offline service worker.)

## Notes
- Principal & interest only — excludes taxes, insurance, PMI/MIP, HOA, and closing costs.
- Future price is derived from the appreciation rate compounded over "months until you buy."
- Equity = projected value change + down payment + principal paid down (excludes selling costs).
- For illustration only; not a commitment to lend. Equal Housing Lender.
