# Production screenshots

Internal note (not rendered into the PDF). Scrub before sharing this tree as a
double-blind review mirror: it names the live platform and its URL below.

Live screenshots of the production admin backoffice, captured 2026-06-29 (the
platform is ROOTS, deployed at degeit-roots.ua.pt). Drop the exported PNGs here
and uncomment the matching `\includegraphics` figure stubs in `main.tex`.

| File to add | Captured view | Intended figure | Section |
|---|---|---|---|
| `admin-dashboard.png` | Admin overview: 215 indicators across 3 areas (Environment 95, Economy 84, Sociocultural 36); data sources API 101 / Upload 116; governance 2% | Production environment / scale + source heterogeneity | Production Deployment and Metrics |
| `add-indicator.png` | "New Indicator" wizard, General information step (bilingual PT/EN metadata: name, area, dimension, unit, scale, source, description) | Source registration by a domain user, no hand-written code | A Source-Agnostic Observatory |
| `indicators-table.png` | Indicators table with per-row Source column (API / Upload badges) | Per-indicator source mix in production | Production Deployment and Metrics |

Notes:
- The platform is anonymized in the manuscript for double-blind review. Crop or blur
  the "ROOTS" logo and any URL/user identifiers before camera-ready submission, or
  regenerate against an anonymized instance.
- The dashboard counts (215 indicators; API 101 / Upload 116) are the *current live*
  catalog as of 2026-06-29; the quantitative results in the paper are anchored on the
  analyzed 149-day dump (see `numbers.tex`). Keep the two clearly distinct in captions.
