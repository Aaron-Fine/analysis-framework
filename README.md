# The Meal Fights Back

A static publication for Aaron Fine's public-source decision analysis. It uses
four paired lenses—ends, commitment, authority, and feedback—and a scored
prediction ledger with explicit time horizons, update triggers, and resolution
criteria. Framework 0.3 (2 October 2026) makes parsimony explicit: begin with an
ordinary baseline, require an incremental contribution from each mechanism,
and stop adding assumptions that do not change the answer.

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
├── closeout/
├── sitemap.xml
├── robots.txt
├── llms.txt
├── assets/
├── styles.css
├── theme.js
├── 404.html
└── _headers
```

**Closed 6 November 2026.** The experiment has ended and framework 0.3 is
final. The ledger records two scored forecasts: water cyber, and Iran, which
resolved to attrition on 31 October. Four forecasts were withdrawn unscored at
closure, each with its last probabilities and dated closing evidence. The
closeout page (`public/closeout/`) summarizes what the record supports: no
demonstrated predictive skill, but explanatory value when signed and built
diverge, when outcomes need several consents, and when coercion meets returned
costs. See `docs/reviews/2026-11-06-closeout.md` for the closeout review.

Public-source analysis and views are personal.
