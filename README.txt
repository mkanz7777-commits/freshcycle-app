FRESHCYCLE OFFLINE-FIRST APP

FILES
- index.html: the app
- manifest.webmanifest: installable web app metadata
- sw.js: offline app-shell cache
- icon.svg: app icon

LOCAL TEST
Open index.html in a browser to use the app and its local data features. When opened as a local file, service-worker installation is not available, but the app itself works in that browser.

INSTALL ON IPHONE / OFFLINE
1. Upload the four app files (index.html, manifest.webmanifest, sw.js, icon.svg) to the root of a free HTTPS static host such as GitHub Pages or Netlify.
2. Open the HTTPS site in Safari while online and wait for it to finish loading once.
3. Tap Share > Add to Home Screen > Add.
4. Launch FRESHCYCLE from its Home Screen icon. Open it once while online so Safari can cache the app shell. It can then reopen offline.
5. Use Insights > Export backup regularly. Data is stored on this device/browser and is not synced automatically.

IMPORTANT
- No paid API, login, account or external database is required for the included features.
- Food date reminders are based only on dates entered by the user; they do not determine food safety.
- Recipe matches are simple ingredient-name matches, not AI.
- AI recognition, family sync, live grocery prices, smart packaging and appliance connections are not implemented in this offline build.
