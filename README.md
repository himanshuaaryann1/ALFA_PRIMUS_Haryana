# ALFA PRIMUS — Haryana Interior Design Website

This is the original static website structure with the full page renderer and supplied hero video retained. Do not upload the Vite-converted `src/` version from the earlier ZIP; that version pointed to the wrong entry file.

## Repository root
- `index.html` — site shell and navigation
- `app.js` — all page content, hash routing and interactions
- `styles.css` — site styling
- `public/Real-Estate-video-SnapYT.App.mp4` — original hero video asset

## Deploy to Vercel
1. Upload these files and the `public/` folder directly to the repository root.
2. Set Framework Preset to **Other**.
3. Leave Build Command empty and set Output Directory to `.`.
4. Deploy.

No npm install or build step is required for this static version. Navigation uses `#/page-slug`, so the page renderer stays on the same shell while switching content. The hero video is served from the included `public/` directory.
