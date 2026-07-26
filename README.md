# The Meal Fights Back

A small, framework-free static publication for Aaron Fine's public-source
decision analysis, prediction tracking, and research notes.

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
├── assets/
├── styles.css
├── theme.js
├── 404.html
└── _headers
```

Public-source analysis and views are personal.
