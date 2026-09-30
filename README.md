# INGCO V44 HTML Viewer

Android WebView wrapper for `INGCO_test_generator_standalone_v44.html`.

The V44 HTML is stored unchanged at:

`app/src/main/assets/index.html`

## GitHub
Upload the whole project to a repository. Then:

Actions → Build INGCO V44 Viewer APK → Run workflow

The generated APK is uploaded as an Actions artifact.

## Permissions
- CAMERA: only for V44's product-code photo scanner.
- INTERNET: only because V44's scanner loads Tesseract.js from its CDN.
- No broad storage permission is requested. PDF/image selection uses Android's system document picker.


## App icon
The launcher icon uses the supplied INGCO GENERATOR artwork.
