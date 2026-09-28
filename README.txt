FINANCE FIX — PWA UPGRADE

This package upgrades the Finance Fix app with:
- Installable PWA manifest
- Android home-screen/app icon assets
- Offline service worker
- Install button when supported by the browser
- Standalone app display mode
- Existing Finance Fix features (budget, savings, transactions, reports, PIN, backup)

IMPORTANT:
A true PWA install requires the files to be served from HTTPS (or localhost). Opening index.html directly as a file can still run the app, but the service worker and automatic install prompt will not work.

Phone-only next step:
1. Put this folder on an HTTPS web host.
2. Open the HTTPS address in Chrome.
3. Tap “Install Finance Fix” or Chrome menu > Add to Home screen.
4. The installed app can work offline after its first successful load.

Security:
This remains a local prototype. PIN and finance data are stored in browser storage and are not bank-grade security. Do not store sensitive banking credentials in it.
