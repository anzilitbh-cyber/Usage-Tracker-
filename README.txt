COMPANY CAR LOG — ANDROID HOME-SCREEN APP

Files:
- index.html: the app
- manifest.webmanifest: install name and icons
- service-worker.js: offline caching
- icons/: home-screen icons

IMPORTANT:
1. This is a manual log. It does not use GPS.
2. Records are stored locally in the browser/device. Export a JSON backup regularly.
3. To install as an app, host these files over HTTPS. Opening index.html directly from a file manager is not enough for PWA installation.
4. Easiest publishing route: create a GitHub repository, upload the contents of this folder, and enable GitHub Pages in the repository's Settings > Pages. Wait for the HTTPS site URL.
5. On Android, open that HTTPS URL in Chrome, tap ⋮, then choose "Install app" or "Add to Home screen".
6. The app has not been independently audited or tested on your specific phone. Test data entry and backup/restore before relying on it for company records.

The app uses browser localStorage; it does not sync across devices or share data with your employer.
