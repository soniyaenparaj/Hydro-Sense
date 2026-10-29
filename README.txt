HYDROSENSE ADVANCED MOBILE DEMO

CONTENTS
- index.html: complete app
- manifest.webmanifest: installable web app metadata
- service-worker.js: basic offline caching
- icon.svg: app icon
- .nojekyll: disables Jekyll processing on GitHub Pages

FEATURES
- Mobile-first Home, Analytics, Alerts, History and Settings tabs
- Simulated turbidity, temperature and water-level values only; no pH
- Local sample history, threshold alerts, threshold settings and CSV export
- Local browser storage; no accounts, cloud sync, physical sensor or external notifications
- PWA install metadata and basic offline cache

DEPLOY ON EXISTING GITHUB REPOSITORY
1. Open https://github.com/soniyaenparaj/Hydro-Sense
2. Choose Add file > Upload files. Upload all files in this folder, not the folder itself.
3. Confirm index.html, manifest.webmanifest, service-worker.js, icon.svg and .nojekyll are at the repository root.
4. Commit directly to main. Do not create a nested folder.
5. Open Settings > Pages and keep Deploy from a branch, main, /(root).
6. Wait for deployment, then open https://soniyaenparaj.github.io/Hydro-Sense/
7. If old content appears, refresh the page. On iPhone Safari, close the old Home Screen app first, revisit the URL, then use Share > Add to Home Screen again.

INSTALL
iPhone: Open the deployed URL in Safari > Share > Add to Home Screen.
Android: Open in Chrome > menu (three dots) > Install app or Add to Home screen.

IMPORTANT
This is a prototype. All values and alerts are simulated and must not be used for drinking-water or health decisions. History/settings are stored only in the browser on the current device.
