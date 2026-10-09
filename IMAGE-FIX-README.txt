HomeNest Picks V4.1 — GitHub Pages Image Fix

IMPORTANT:
This version fixes the broken product-image paths seen on GitHub Pages.

Upload ALL files in this folder to the GitHub repository (replace the old site files).

Stable product images:
- product-1.jpg through product-6.jpg

Gallery images:
- gallery-1-1.jpg through gallery-6-4.jpg

The HTML now uses relative paths only, so it works on GitHub Pages project sites.
It also has a fallback: if a gallery image is missing, the matching product-N.jpg is used instead.

After uploading, do a hard refresh in Chrome (or open the site in Incognito) because GitHub Pages/browser caching can temporarily show the old version.
