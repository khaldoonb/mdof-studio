MDOF Dynamic Response Studio - iPhone / iPad home-screen app
============================================================

A. Publish (once, free, about 5 minutes)
  1. Sign in at github.com and create a new PUBLIC repository (e.g. "mdof-studio").
  2. Upload ALL files in this folder (index.html, manifest.webmanifest, sw.js, 3 icons).
  3. Repository Settings > Pages > Source: "Deploy from a branch" > main > /(root) > Save.
  4. After a minute the app is live at  https://<your-username>.github.io/mdof-studio/

B. Install on iPhone / iPad
  1. Open that address in Safari and wait for the page to load fully.
  2. Tap Share > Add to Home Screen > Add.
  3. Launch it from the new icon: full screen, and it works offline after the first load.

C. Updating
  Replace index.html in the repository, and change VERSION in sw.js
  (e.g. 'mdof-v1' -> 'mdof-v2') so devices download the new version.

Note: the map background tiles (OpenStreetMap/Carto) still need internet;
everything else runs offline.
