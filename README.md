# Campus Market

An interactive look at completed home sales across 11 university markets.

## What this site is for

Campus Market helps students, families, and community members compare home-sale prices in college towns. Choose a university to see its campus-area sales, city medians, and sales by year.

## Live site

[Open Campus Market](https://belladove1128-arch.github.io/college-town-housing/)

## Data notes

The page reads `data/college_town_home_sales.csv` in the browser. All displayed sale counts and median prices are computed from those records. Sales below $10,000 are excluded because the source notes identify implausibly low prices. The same rule is applied to every summary. Repeated addresses are kept because they may represent distinct units or transactions. The page does not use `home_type`, which the data description sheet says is often misclassified.

Campus areas use the dataset's nearest-campus assignment. Distances are straight-line distances. Values were collected from public listings in March 2026 and are not independently verified against county records.

## Tools

- OpenAI ChatGPT Codex for HTML, CSS, JavaScript, and data-analysis implementation
- GitHub Pages Actions workflow for static hosting
- Plain HTML, CSS, and JavaScript; no third-party chart library

## Citation

College-town home sales dataset, version 1.0 (2026). University of Illinois-Deloitte Foundation Center for Business Emerging Technologies. Data collected March 2026.
