# LABZ launcher (public, no health data)

Prepared update for https://nuclearay.github.io/labz/ (repo `nuclearay/labz`).

This folder is ready to copy into the public repo and push when you want. It has **not** been pushed.

Contains:

- `index.html` — instant branded splash, `preconnect` / `dns-prefetch` to `script.google.com` and `script.googleusercontent.com`, same iframe URL as today.
- `chart.umd.min.js` — Chart.js v4 (public library, no health data). The private Apps Script app lazy-loads this after the lab list paints. Publish this file **before or with** the Apps Script v10 deploy, or the first chart open will 404 until it is live (the app also tries `/vendor/chart.umd.min.js` as a local-test fallback).
- `icons/labz-192.png`, `icons/labz-512.png`, `manifest.webmanifest` — unchanged from the live site.

Do not add sheet data, lab names, or any health information to this repo.
