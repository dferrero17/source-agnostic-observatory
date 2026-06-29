# Production screenshots

Drop the exported PNGs here and uncomment the matching `\includegraphics` figure
stubs in `main.tex`. Screenshots of the production admin backoffice, captured
2026-06-29.

| File to add | Captured view | Intended figure | Section |
|---|---|---|---|
| `admin-dashboard.png` | Admin overview: total indicator count across three domains, with the data-source split (API vs uploaded file) | Production environment / scale + source heterogeneity | Production Deployment and Metrics |
| `add-indicator.png` | "New Indicator" wizard, general-information step (bilingual metadata: name, area, dimension, unit, scale, source, description) | Source registration by a domain user, no hand-written code | A Source-Agnostic Observatory |
| `indicators-table.png` | Indicators table with the per-row Source column (API / upload) | Per-indicator source mix in production | Production Deployment and Metrics |

Double-blind hygiene before any figure ships or this tree is shared as a review
mirror:
- Crop or blur the platform logo and any URL, instance, or user identifiers in
  every screenshot.
- The dashboard's *current live* counts are a fingerprint of the deployment and
  differ from the paper's 149-day dump figures; keep captions anchored on the dump
  numbers in `numbers.tex`, not on live counts.
