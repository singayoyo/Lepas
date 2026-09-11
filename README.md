# LEPAS South Africa Marketing Report

Static marketing performance report for LEPAS South Africa's August 2026 paid media campaign.

## Open Locally

```sh
python3 -m http.server 8087 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:8087/
```

## Main Files

- `index.html` - deployment entry point.
- `main report template.html` - working report template.
- `assets/lepas-report-data.js` - report data exported from the workbook.
- `Lepas_Aug2026_Media_Performance.xlsx` - source workbook with campaign, creative, fatigue, and budget forecast tabs.
- `design.md` - local working LEPAS design guide.
- `PRODUCT.md` - report product brief.

## Deployment

This is a static site. It can be deployed with GitHub Pages, Vercel, Netlify, or any static file host.
