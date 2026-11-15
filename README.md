# Khawlan Alawadhi — Portfolio

A responsive portfolio in English, Arabic (right-to-left), and Dutch.

## Publish with GitHub Pages

1. Upload the contents of this folder to the root of `KhawlanYE/portfolio`.
   `index.html` must be beside `README.md`, not inside another folder.
2. Keep the `ar` and `nl` folders intact.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose **main** and **/ (root)**, then **Save**.
6. Wait for the Pages deployment to finish. The Actions tab shows progress.

Website: https://khawlanye.github.io/portfolio/
Arabic: https://khawlanye.github.io/portfolio/ar/
Dutch: https://khawlanye.github.io/portfolio/nl/

The existing `khawlanye.github.io` repository is not changed.

## Files

- `index.html`: English page
- `ar/index.html`: Arabic page
- `nl/index.html`: Dutch page
- `style.css`: shared styling
- `app.js`: shared interactive behavior
- `locale-en.js`, `locale-ar.js`, `locale-nl.js`: language and project content
- `.nojekyll`: serve these files without Jekyll processing

No installation or build step is needed. Paths are configured for `/portfolio/`.
If the repository name or domain changes, update asset paths, language links,
canonical URLs, and alternate-language URLs in all three HTML files.
