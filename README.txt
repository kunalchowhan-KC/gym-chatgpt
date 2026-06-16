Routine Tracker PWA

Replace your repo root files with:
- index.html
- script.js
- style.css
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png

Optional:
- .github/workflows/pages.yml

Notes:
- Your existing localStorage + JSON file flow is preserved.
- The app now registers a service worker and exposes an Install App button.
- The cache name is versioned as routine-tracker-pwa-v1.

GitHub Pages:
- Keep .nojekyll in the repo root.
- Push to main and use the Pages workflow if you want Actions-based deploys.
