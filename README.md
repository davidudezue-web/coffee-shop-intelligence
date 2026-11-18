# Coffee Shop Intelligence — Interactive Portfolio Case Study

Prepared for **Chukwuemeka David Udezue** (Crafttmeal), Data Analyst / BI & Visualisation Specialist, Blossom Graphviz Concept.

## What is inside

- `index.html` — responsive single-page website
- `assets/styles.css` — visual styling, 3D-inspired hero, accessibility and responsive layouts
- `assets/app.js` — interactive sales/demand/inventory charts, workflow selector, chart gallery and CSV export
- `assets/data.js` — pre-aggregated, source-derived analysis figures used by the interactive charts
- `assets/*.png` — original analysis chart images
- `downloads/*.xlsx` — prepared Excel workbook with cleaning log
- `downloads/*.pdf` — full documented process case study
- `downloads/*.pptx` — original 11-slide AI analysis project presentation

All downloads are self-contained links. The site does **not** upload or transmit visitors' data. The only external dependency is optional Google Fonts; fonts fall back to local system fonts if unavailable. All charts run with native browser JavaScript and SVG and require no charting CDN.

## Preview on your Windows computer

1. Extract the ZIP archive.
2. Double-click `index.html` to preview (most features work without a server).
3. For more reliable testing, open CMD inside the extracted folder and run: `python -m http.server 8000`.
4. Open `http://localhost:8000` in your browser.

## Publish for a shareable website (GitHub Pages)

1. Create a **public** GitHub repository named `coffee-shop-intelligence`.
2. Upload `index.html`, `assets/`, `downloads/` and `README.md` to the repository **root**. Keep the folder structure.
3. Open repository **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Once Pages publishes, the usual URL format is `https://YOUR_GITHUB_USERNAME.github.io/coffee-shop-intelligence/`. Use the actual URL shown in Settings → Pages; it is not live before you publish.
5. Open every menu item, toggle the three chart tabs, test CSV download, and download the PDF/XLSX/PPTX from the published URL.

Alternative: drag the contents of the extracted folder into Netlify's manual deployment interface; use the URL Netlify actually issues.

## Important integrity notes

- This is a historical business analytics **case study**. No client engagement, commercial financial impact, cloud deployment, or completed Power BI implementation is claimed.
- The cleaned workbook preserves source fields and review flags rather than silently changing doubtful data.
- Recorded revenue is presented in source currency units, because the sales fact table does not independently label the transaction currency.
- The source analysis presentation and process PDF describe the original academic exercise; the public website itself is a professional case-study narrative. Review the contents of all downloadable documents before publishing, especially if you later add personal details to the presentation.
- The data workbook contains only the four analytic datasets and cleaning log; do not upload the broader original workbook containing customer or staff records without permission and a privacy review.

## Update your own details

Edit `index.html` (Ctrl+F on the email address, LinkedIn URL, name and company). Save and re-upload the file to GitHub. The logo is a custom typographic mark, not an official BGC logo.

## Method

Source: Excel coffee shop data, prepared workbook with 15-step log, AI-assisted sales/customer-demand/pastry analyses, and supporting historical charts. Interactive data is built from the recorded analysis and checked to reconcile at 233,635.95 recorded revenue and 4,500 recorded waste units.
