# The Meal Fights Back

A static publication for Aaron Fine's public-source decision analysis. It uses
four paired lenses—ends, commitment, authority, and feedback—and a scored
prediction ledger with explicit time horizons, update triggers, and resolution
criteria.

## Local preview

From the repository root:

```bash
python3 -m http.server 8000 --directory public
```

Then open <http://localhost:8000>.

## Deployment

The site is plain static HTML, CSS, and JavaScript. Configure the hosting provider with no framework or build command and use `public` as the output directory.

## Structure

```text
public/
├── index.html
├── framework/
├── prediction-ledger/
├── research-foundations/
├── sitemap.xml
├── robots.txt
├── llms.txt
├── assets/
├── styles.css
├── theme.js
├── 404.html
└── _headers
```

The active ledger covers Iran, two linked Greenland forecasts, the post-court
tariff regime, and administrative-state restructuring. The resolved
critical-water cyber forecast remains visible with its history and score.

Public-source analysis and views are personal.
