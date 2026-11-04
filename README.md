# TIP Member District Homeschool Explorer

A static, TIP-branded dashboard with county-level homeschool enrollment, education-market shares, and Opportunity Scholarship funding for 20 member districts.

## Publish on GitHub Pages

1. Sign in to GitHub and create a **public** repository named `tip-homeschool-explorer`.
2. Upload the files in this folder to the repository's top level, so `index.html` appears immediately when you open the repository. Upload the extracted files, not this ZIP file.
3. Commit the files to the `main` branch.
4. Open **Settings > Pages**.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
6. Select branch **main**, folder **/(root)**, then **Save**.
7. GitHub will display the published address, typically `https://YOUR-USERNAME.github.io/tip-homeschool-explorer/`.

GitHub may take up to 10 minutes to publish. No build command, ChatGPT account, API key, or database is required by the dashboard.

## Files

- `index.html`: the dashboard, with embedded data and county boundaries.
- `data.json`: downloadable data copy.
- `tip-homeschool-report.pdf`: the report opened by the dashboard's PDF report button.
- `.nojekyll`: serves the files directly, without Jekyll processing.

## Data and interpretation

Source data reviewed November 4, 2026. County figures are associated with member districts and are not exact district-resident counts. Homeschool snapshots cover 2023-24 through 2025-26. Market share is available for matched 2024-25 data. Opportunity Scholarship county figures follow student residence, while school-level payments follow the receiving school. County school lists use the DNPE January 2026 directory; unambiguous name-plus-city matches attach scholarship payments. Unmatched entries do not establish zero payments. See the dashboard's Sources & methods tab for official sources and detail.

## Maintenance

Replace these files in the same repository to publish an updated dashboard. Review all embedded data before changing it. Source data and school-directory dates should be updated together with the displayed notes.

This package is independent of ChatGPT Sites and contains no hosting credentials or account connection settings. No software license has been assigned; repository ownership and any future licensing should be decided by TIP.

Official setup instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
