# Passband

Static web app. No build step and no server code: serve this folder over HTTPS.

## Deploy
- **Netlify:** drag the folder onto app.netlify.com/drop.
- **GitHub Pages:** push the folder contents to a repository and enable Pages for the main branch.
- **Any static host:** upload `index.html`, `manifest.webmanifest`, `sw.js` and `icons/`.

## Install
Open the deployed address in Chrome, Edge or Safari. Use the Install button in the page header, the browser's install icon, or "Add to Home Screen" on a phone. After the first visit it also works offline. Fonts load from Google Fonts on the first visit and are cached afterwards; without them the app falls back to system fonts.

## Run locally
`python3 -m http.server 8000` in this folder, then open http://localhost:8000.
