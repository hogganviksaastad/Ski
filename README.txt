Full Ski Selector app package for GitHub Pages
Files included:
- index.html (full interactive app)
- manifest.json
- sw.js
- apple-touch-icon.png
- icon-192.png
- icon-512.png
- import_report.json

Deployment:
- Upload all files directly to repository root.
- Do NOT upload the "local" folder or SkiEssentials_2027_sheet.xlsx - they are
  working files for the data build, not part of the deployed app.
- Enable GitHub Pages from main branch / root.
- Open the URL in Safari on iPhone.
- Tap Share > Add to Home Screen.

skiessentials-2027 changes:
- Replaces the old Jonas_master_ski_sheet_FINAL_V2.xlsx dataset with the
  SkiEssentials 2027 Ski Test (skiessentials.com), Men's Frontside and
  Men's All-Mountain categories.
- Loads 207 ski rows, built from 1,528 individual tester score cards across
  214 ski pages (7 skis were excluded: 6 had no tester scores yet on the
  site, 1 had a broken spec field on the source page). See import_report.json
  for the full breakdown, including which fields are measured tester
  averages and which are rule-based interpretations.
- Product links point directly to each ski's SkiEssentials 2027 Ski Test
  page instead of a Google search fallback.
- Keeps the iPhone/mobile-friendly layout, weighting sliders, presets,
  radius-first turn logic, structured Top 3 comments, and winner ability
  chart unchanged.
- Service worker cache name and in-app build labels are updated for this
  package, so installed iPhone PWAs pick up the new dataset automatically
  on next open.
- The previous dataset (165 rows) is preserved in local/backup-final-v2/
  in case it's needed again; that folder is not part of the deployed app.
