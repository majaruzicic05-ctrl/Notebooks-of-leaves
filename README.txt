AUTUMN MASTER NOTEBOOK — INSTALLABLE APP PACKAGE

This folder is a Progressive Web App (PWA).

Files:
- index.html — the notebook
- manifest.webmanifest — app identity/icon/full-screen settings
- sw.js — offline support
- icons/ — home-screen icons

To install on Android:
1. Put this folder on any HTTPS static web host (GitHub Pages, Netlify, Cloudflare Pages, etc.).
2. Open the hosted page in Chrome on the tablet.
3. Chrome menu → Add to Home screen / Install app.
4. It will then open in its own full-screen app window and continue to work offline after first load.

Your notebook data is stored locally in the browser/app storage on that device.
Use the notebook's Export button for backups.
