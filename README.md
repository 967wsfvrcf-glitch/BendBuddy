# BendBuddy v0.3 — Field Sheets

Free, static progressive web app for EMT bending helpers and general electrician quick-reference sheets.

## Files
- `index.html` — app interface, calculators, diagrams, and searchable field sheets
- `manifest.webmanifest` — install metadata
- `sw.js` — offline caching service worker

## Update on GitHub Pages from iPhone
1. Open your BendBuddy repository on GitHub in Safari.
2. Open `index.html`, tap the pencil/Edit button.
3. Select all existing code and replace it with the new `index.html` from this package. Save/commit to `main`.
4. Repeat for `sw.js` and `manifest.webmanifest`.
5. Wait a few minutes, then reload the live site. If the installed Home Screen version looks old, open the site in Safari first and reload; service-worker caches can take a moment to update.

## Safety
The field sheets are general reminders, not electrical design advice. Always follow the locally adopted code, approved plans, manufacturer instructions, qualified-person requirements, and employer/site procedures. Verify calculations and device ratings before use.
