# Meridian Treasury Intelligence — public demo

Independent executive-facing banking analytics case study grounded in publicly disclosed Seacoast Banking Corporation of Florida data through **Q3 2026**. This repository is **not affiliated with or endorsed by Seacoast Bank**. Future financials, scenario shocks, security-category duration / convexity / spread proxies, and synthetic customer records are illustrative, not verified bank forecasts or model estimates.

## Live demo (after GitHub Pages activation)

`https://YOUR-USERNAME.github.io/meridian-treasury/`

Replace `YOUR-USERNAME` with the GitHub account owner in the URL. **Do not publish a URL on a resume until it works in a logged-out browser.**

## Quick publish on GitHub Pages

1. Make a **public** GitHub repository named `meridian-treasury` (GitHub Free supports Pages for public repositories).
2. Unzip the `Meridian_GitHub_Pages_Ready.zip` package and upload **all files and folders inside** `Meridian_GitHub_Pages_Ready` to the repository root. `index.html`, `.nojekyll`, `dashboard.html`, `styles.css`, `README.md`, plus `downloads/`, `images/`, `source/` must be at root, not enclosed in an extra directory. In GitHub use **Add file → Upload files**.
3. Open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then **Save**.
4. Open the published project URL and test `dashboard.html`, the Excel download, and PDF links.
5. Add the final URL to your resume under **Selected Projects** and to LinkedIn's **Featured** section.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Files

- `index.html` — public-facing case study landing page
- `dashboard.html` — complete standalone v4 interactive dashboard, in browser; no backend
- `downloads/Meridian_Treasury_Model.xlsx` — editable Excel workbook, served as a **download**, not an in-browser workbook
- `downloads/*.pdf` — one-page independent executive briefs
- `methodology.html` — executive explanation of model boundaries
- `source/` — Python calculation engines, validations, source data, full technical methods
- `images/` — genuine screenshots from the v4 dashboard

## Privacy / publication

Do not add a resume, private contact details, bank proprietary files, API keys, client records, or proprietary position-level data here. GitHub Pages publishes to the open internet. The dashboard is entirely client-side, with no analytics tracking, server uploads, or user accounts. All customer-level examples are synthetic. The website is **not** a production treasury or ALM system.

## Excel in browser

GitHub Pages only hosts the XLSX download; it cannot run desktop Excel calculations in the browser. For a separate preview, store a copy on OneDrive, use **Share → Anyone with link can view** (if available for your account), then link to that read-only preview from your website or resume. The GitHub Pages downloadable copy remains the source-of-record portfolio artifact.

## Tech

Static HTML, CSS and JavaScript for the dashboard. Python modules and unittest cases under `source/`. Uploaded workbook requires Excel or a compatible spreadsheet application. The static site can be deployed without Python, Node, CI, or a paid hosting service.
