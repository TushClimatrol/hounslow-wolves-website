# Hounslow Wolves FC — website

Official website for Hounslow Wolves Football Club (est. 2020, West London).

Live site: https://hounslow-wolves.onrender.com

- `index.html` — the whole site in one file (styles, scripts, logos and gallery photos are embedded). Open it in any browser.
- Hosted as a static site on Render; every push to `main` redeploys automatically.

## Editing content

All club data lives in the `CONFIG` block near the top of the `<script>` in `index.html`:
squads, fixtures and results, league table, news, managers' emails, shop items and the subs settings.

## Subs

The "Pay your subs" section reads the secretary's attendance sheet. Publish the Google Sheet tabs
(Attendance, Players, Settings) to the web as CSV and paste the links into `CONFIG.subsSheets`.
Until that is set, the page shows the built-in demo snapshot.
