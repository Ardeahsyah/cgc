# Sustainable MSME Impact & Guarantee Intelligence Dashboard

A responsive, static dashboard designed from the 13 supplied visual references. It is suitable for GitHub Pages and reads its content from an Excel workbook in the browser.

## Deploy on GitHub Pages

1. Create a GitHub repository.
2. Upload the entire contents of this folder, preserving the `css`, `js` and `data` folders.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

## Update dashboard data

1. Open `data/dashboard-data.xlsx` in Microsoft Excel.
2. Keep the header names unchanged.
3. Update values or add rows within the existing tables.
4. Save the workbook and replace the file in the GitHub repository.
5. Refresh the website.

## Workbook sheets

- `Settings`: organisation, period and workbook controls
- `Pages`: sidebar pages, titles and descriptions
- `KPIs`: all KPI cards, RAG status and sparkline series
- `Alerts`: executive attention items
- `Funnel`: inclusion funnel
- `States`: Malaysia state-level values
- `PFI`: participating financial institution data
- `Disclosure`: disclosure-readiness pillars
- `Operations`: own-operations footprint

## Important hosting note

The Excel workbook is fetched by JavaScript. Opening `index.html` directly from a local folder may be blocked by browser security. Use GitHub Pages, VS Code Live Server, or run `python -m http.server` from the project folder for local viewing.

## Technology

- HTML5
- Responsive CSS
- Vanilla JavaScript
- SheetJS browser library for `.xlsx` parsing
- No backend or database required
