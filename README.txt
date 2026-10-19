SONORA MOBILE PWA — QUICK START

WHAT THIS IS
A mobile-first installable web-app package for SONORA. It preserves the existing JavaScript Offline Music Lab and adds a web app manifest, icons, and a service worker for offline app-shell caching.

IMPORTANT
A PWA cannot be installed from a file:// download directly. Android Chrome/Samsung Internet generally require the site to be served over HTTPS. This ZIP does not itself publish the app online.

FREE DEPLOYMENT OPTION
You can publish these files using a free static host such as GitHub Pages. A GitHub account may be required; the host's current policies and limits apply. From your Samsung phone:
1. Extract this ZIP using My Files.
2. Open GitHub in your browser and sign in or create an account.
3. Create a new public repository, e.g. sonora-mobile.
4. Upload the files and folders in this package, keeping their names and folder structure.
5. Enable GitHub Pages for the repository (Settings → Pages → deploy from the main branch/root, if available).
6. Open the HTTPS Pages URL on your phone.
7. In Chrome or Samsung Internet, use the browser menu and choose “Install app” or “Add to Home screen” if offered.

NOTES
- No Node.js, Python installation, API key, subscription, or paid music API is required for the current browser synthesizer.
- The current engine makes synthesised instrumental sketches; it is not yet a trained text-to-song AI model and does not generate realistic vocals.
- Service-worker/offline caching only works when served from HTTPS (or localhost).
- This is a starter package; test audio playback, WAV export, installability, and offline launch on the actual device.
