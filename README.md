# Technical Project Tool v0.1

Browser-only workbook importer and validator. Project files selected by the user are processed in the browser and are not committed to this repository.

## Local use

```bash
npm install
npm run dev
```

## GitHub Pages

1. Upload these files to the repository root and commit to `main`.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, select **GitHub Actions**.
4. Open the **Actions** tab and confirm the Pages workflow completes.

Repository base path is configured as `/Technical-Project-Tool/`.

## Current scope

- Reads XLSX, XLS and CSV files.
- Detects worksheets and likely header row.
- Maps real source columns.
- Validates real rows without silently modifying source values.
- Exports an XLSX with Beam by Beam Summary, Source Data and Validation Log.

This application produces a review record, not design approval or technical sign-off.
