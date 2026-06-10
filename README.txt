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
- Enable GitHub Pages from main branch / root.
- Open the URL in Safari on iPhone.
- Tap Share > Add to Home Screen.

jonas-master-ski-sheet-final-v2 changes:
- Uses the full Jonas_master_ski_sheet_FINAL_V2.xlsx workbook as the source for skis, ratings, comments, and technical geometry.
- Loads 165 ski rows from the workbook.
- Preserves existing product links where an exact model/length or model-level match exists; otherwise falls back to a search link.
- Keeps the iPhone/mobile-friendly layout, weighting sliders, presets, radius-first turn logic, structured Top 3 comments, and winner ability chart.
- Service worker cache name and in-app build labels are updated for this package.
