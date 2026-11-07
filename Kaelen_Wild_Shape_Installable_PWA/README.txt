KAELEN WILD SHAPES — INSTALLABLE PWA

1. Upload all files and the icons folder to an HTTPS static site, such as GitHub Pages, Netlify, or Cloudflare Pages.
2. Open the resulting URL on Android in Chrome.
3. Browser menu > Install app / Add to Home screen.
4. Tap the new icon to launch.

Android Back closes an open stat block first.
Selections are saved in localStorage under the same site origin. Keep the same URL for updates.
To update: replace index.html and bump CACHE version in sw.js (e.g. v2). Reopen the app online; it refreshes from the server and can be used offline.
Before moving between sites or devices, use Export backup / Import backup.
5etools links require an internet connection.

This is a PWA, not a compiled Android APK. Opening index.html directly from Files will not install the PWA or register offline caching.
