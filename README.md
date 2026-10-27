# Devesh Properties — Royal Pride Plot Studio

Static GitHub Pages prototype for plot-by-plot discovery and local inventory editing.

## Deploy
The workflow at `.github/workflows/pages.yml` publishes this static site through GitHub Pages.

## Prototype limitations
- Plot tiles are a schematic inventory finder, not an official surveyed/site plan.
- All 95 plot statuses default to **Pending**. Prices, areas, dimensions and facing directions stay blank until verified and entered.
- Broker changes and enquiries are stored in the current browser's local storage only. They do not sync between customer devices or to a broker.
- Do not use this prototype to represent title, regulatory approval, RERA status, exact plot boundaries, or confirmed availability.
- Before live commercial use, connect a secure API/database, authentication and broker roles, validated plot-plan geometry, and a broker notification channel. Verify property details against authorised documents.

## Files
- `index.html` — customer plot finder, broker local inventory editor, CSV import/export, and local enquiry register.
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow.
