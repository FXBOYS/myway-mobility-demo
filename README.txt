MYWAY MOBILITY — PASSENGER DEMO
================================
This is a front-end demonstration prototype, not a live transport service.

FILES
- index.html: passenger app
- manifest.webmanifest: installable web app metadata
- sw.js: basic service worker for app shell caching
- assets/myway-logo.png: supplied MYWAY logo
- assets/myway-icon-192.png and myway-icon-512.png: app icons

HOSTING
Upload the CONTENTS of this folder to the root of a public GitHub repository.
Enable GitHub Pages from Settings > Pages > Deploy from a branch > main > /(root).

FEATURES
- Responsive passenger-first interface
- OpenStreetMap map (internet connection required for map tiles)
- Demo destination route previews
- Demo ride booking preview
- Interactive simulated SOS confirmation and alert screen
- Trusted contacts sample panel
- Installable PWA metadata and MYWAY app icon

IMPORTANT DEMO LIMITATIONS
- SOS is simulated and does not contact emergency services, MYWAY staff or trusted contacts.
- Booking does not dispatch a real driver or charge a passenger.
- Map route is illustrative and destinations use sample coordinates.
- GPS button requests browser location only after user permission.
- No camera feed, recording, payments, accounts or live backend are connected.
- Do not enter real personal information.
- HTTPS hosting is required for installability and geolocation in most browsers.
