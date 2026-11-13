MY BARCODE LIBRARY — iPHONE PWA STARTER

Included:
- index.html: the app
- manifest.webmanifest: installable app metadata
- sw.js: offline app-shell caching

IMPORTANT:
This app stores product records and barcode photos in IndexedDB in the browser on the device.
It does not upload photos to a server. Clearing Safari website data or deleting the browser's
stored website data can erase the library. There is no cloud sync or backup in this first version.

TO INSTALL ON IPHONE:
1. Host these files at an HTTPS address (for example, a private GitHub Pages site).
2. Open that HTTPS address in Safari on the iPhone.
3. Tap Share, then Add to Home Screen.
4. Launch "My Barcode Library" from the Home Screen.

The app requires HTTPS for reliable service-worker/offline installation. Opening the HTML
directly from the Files app is not the recommended install method.
