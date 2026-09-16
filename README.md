# ফর্ম অটোফিলার — Excel থেকে Google Form

A single-page, client-side tool that reads rows from an Excel/CSV file and submits them into a Google Form automatically, using the form's `entry.xxxxx` field IDs.

## Features
- Paste a Google Form pre-filled link or the raw payload to auto-detect `entry.*` field IDs
- Upload an `.xlsx`/`.csv` file and map its columns to form fields
- Preview and submit rows one at a time, or submit all rows in sequence
- Runs entirely in the browser — no backend/server required

## Usage

### Option A — GitHub Pages (recommended)
1. Push this repo to GitHub.
2. Go to **Settings → Pages**, set the source to the `main` branch (root), and save.
3. Visit the published URL (e.g. `https://<username>.github.io/<repo>/`).

### Option B — Run locally
Just open `index.html` directly in a browser — no build step or server needed.

## Tech
- Pure HTML/CSS/JS, no build tools
- Uses [SheetJS (xlsx.js)](https://github.com/SheetJS/sheetjs) via CDN to parse spreadsheet files

## License
MIT — see `LICENSE`.
