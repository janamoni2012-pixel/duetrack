# DueTrack V2

A responsive personal money assistant MVP built for static hosting.

## Features
- Income and expense tracking
- EMI / bill / custom payment reminders
- One-time, monthly and yearly reminders
- Safe-to-spend calculation
- Money Calendar
- Monthly analytics and category breakdown
- Browser notifications where supported
- Local browser storage
- JSON backup / restore
- PWA install support
- Offline caching
- Mobile responsive UI

## GitHub Pages

Upload the **contents of this folder** to the root of your `duetrack` repository:

- `index.html`
- `css/`
- `js/`
- `assets/`
- `manifest.json`
- `service-worker.js`
- `README.md`

Then use:
Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

## Important MVP limitation
Financial information is stored locally in the user's browser. It is not synced between devices. Browser notifications are not guaranteed when the browser is fully closed. A production version would require a secure backend and push-notification infrastructure.

## No Python backend yet
This version targets GitHub Pages, which cannot run Flask/Python. A backend should only be added when accounts, cloud sync, or server-triggered reminders are implemented.
