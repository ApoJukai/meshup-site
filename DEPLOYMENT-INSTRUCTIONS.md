# MeshUp UI Fixes Deployment

## Improvements
- Corrected secondary-button text contrast.
- Rebuilt the Clear Expectations section as styled, accessible card buttons.
- Rebuilt the footer controls as real clickable buttons and links.
- Added a working policy dialog with keyboard focus restoration and Escape-key closing.
- Replaced the static app-preview collage with seven individual optimized WebP screens.
- Rebuilt carousel navigation for arrows, dots, keyboard, swipe, and mouse drag.
- Added morph-style blur, scale, clipping, and 3D transitions.

## Deploy
Upload `index.html` together with the complete `assets` directory. The relative path must remain `assets/<screen>.webp`. Clear the hosting/CDN cache after replacing the old version.

## Test
1. Open the page through an HTTP/HTTPS server, not only a file preview.
2. Test all eight Clear Expectations cards.
3. Test all footer policy buttons.
4. Test the carousel arrows, seven dots, keyboard arrows, swipe, and mouse drag.
5. Test desktop and mobile widths and the reduced-motion setting.
