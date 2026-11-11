# FDE Journey PWA
Personal Android-friendly roadmap tracker.

## Features
- 6 phases, 30 tasks, approximately 18 months
- Progress percentage and phase completion
- Automatic next incomplete task and manual focus selection
- Local-only browser storage; no login or server
- JSON export/import backup
- Offline cache after first successful online load
- Automatically follows system light/dark mode

## Publish with GitHub Pages
1. Create a GitHub repository (for example `fde-journey`).
2. Upload `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.svg` to its root.
3. Repository Settings → Pages → Deploy from a branch → `main` and `/ (root)` → Save.
4. Open the published HTTPS URL in Chrome on Android.
5. Chrome menu ⋮ → Add to Home screen / Install app.

A PWA needs HTTPS (or localhost) for installation and offline service-worker features. Opening `index.html` directly is only a preview.

## Backup
Use Export backup to download a JSON file. Importing a backup replaces current progress. Export regularly; clearing browser/site data can erase local progress.

## Limitation
This PWA does not provide a native Android home-screen progress widget. That can be added in a later native Android version. This starter has not been tested on your specific device/browser.
