# Penguin Pass

A small browser-based Leaving Certificate revision quiz with daily runs, subject selection, streak tracking, and progress saved in the browser.

## Run locally

Open `index.html` in a modern web browser. No build step or package installation is required.

## Publish with GitHub Pages

1. Create a new repository on GitHub.
2. Upload `index.html`, `README.md`, and `.nojekyll` to the repository's **root** (top-level) folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)` folder, then save.
6. Wait for GitHub Pages to publish; the site URL will appear in the Pages settings.

## Notes

- The site is self-contained; it does not require image, CSS, or JavaScript files alongside `index.html`.
- Google Fonts are loaded from Google Fonts when an internet connection is available. System fallback fonts are included.
- Quiz progress is stored in the visitor's browser using `localStorage`; it is not synced between devices or browsers.
