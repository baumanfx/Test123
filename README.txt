Esslingen Station Radius Notifier v0.1.0

Purpose
- Turns the app background green when you are within the configured radius of Esslingen (Neckar) station.
- Sends a browser notification on entry into the radius.

Important
- This build is intended to be served over HTTPS.
- For Android/mobile notifications, install it as a PWA after opening the HTTPS URL in Chrome.
- Opening index.html directly from Downloads or a document viewer will usually not provide the required browser security context for notifications and may also block geolocation permission prompts.

Files
- index.html
- sw.js
- manifest.webmanifest
- icon-192.png
- icon-512.png

Suggested deployment
- Upload the full folder contents to an HTTPS host.
- Open the hosted URL in Chrome.
- Use Chrome's install/add-to-home-screen option.
- Open the installed app, tap Grant permissions, then Start monitoring.
