# Goal Tracker PWA (GitHub Pages)

## Publish
1. Create a new GitHub repository (Public is simplest), e.g. `goal-tracker`.
2. Upload **all contents** of this folder to the repository root. `index.html` must be at the root, not inside another nested folder.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main`, folder `/(root)`, then Save.
6. Wait for GitHub Pages to publish. Open the HTTPS URL GitHub shows.

## Install on Android
1. Open the https://nihad-006.github.io/agoal-tracker/ Pages URL in Chrome.
2. Tap ⋮ → **Install app** (or **Add to Home screen**).
3. Confirm Install.

## Notes
- The service worker and offline cache require HTTPS; GitHub Pages provides HTTPS.
- The image OCR feature downloads Tesseract.js from a CDN on first use, so OCR initially needs internet.
- Browser localStorage is origin-specific. Data in the old `content://` file may not automatically transfer to the GitHub Pages website. Export/backup existing data from the old app before switching, if the app provides that option.
