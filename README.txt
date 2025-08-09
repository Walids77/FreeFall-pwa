Free Fall Calculator — PWA Package
Built: 2025-08-09T14:58:03

How to use:
1) Upload the entire 'freefall-pwa' folder to any static host (Netlify, Vercel, GitHub Pages, etc.).
2) Open the site on:
   - Android/Chrome: tap menu → Install app (or you may see an Install prompt).
   - iPhone/Safari: Share → Add to Home Screen.
3) It opens full-screen like a native app.
4) Files you can customize:
   - manifest.webmanifest: app name, colors, icons.
   - sw.js: add more files to ASSETS if you want them available offline.
   - index.html: your original app + minimal PWA hooks added.

Notes:
- External images (icons8 emoji URLs) may not be cached by the service worker due to CORS; that's normal.
- If you change files, bump the CACHE version in sw.js (e.g., freefall-v2) so updates reach users.