# MeshUp Website Swipe Preview Update

## What changed
- Replaced the single composite app-preview image with seven individual phone-screen images.
- Added previous and next buttons, progress dots, keyboard navigation, and touch/mouse dragging.
- Added a smooth blur, scale, clip, and 3D morph-style transition.
- Added live HTML titles and descriptions for each application screen.
- Added reduced-motion accessibility support.

## Use
The standalone HTML file is self-contained and can be opened directly in a browser. No build step is required.

## Deploy
Rename `meshup-website-swipe-preview.html` to `index.html` and upload it to the existing static host, replacing the previous website file. Clear the browser or CDN cache if the previous preview continues to appear.

## Separate assets
The ZIP also includes the seven WebP images under `assets/`. The standalone HTML already embeds the same images, so those files are optional unless the site is later refactored to use external assets.
