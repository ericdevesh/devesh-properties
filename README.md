# Devesh Properties — Royal Pride Plot Studio

Static site prototype for plot-by-plot discovery and local inventory editing.

## One-time GitHub Pages setup
The repository is connected to a deployment workflow, but GitHub blocks the workflow token from enabling Pages the first time. Complete this once as the repository owner:

1. Open **[Settings → Pages](https://github.com/ericdevesh/devesh-properties/settings/pages)**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions** and save.
3. Open **[Actions → Deploy Plot Studio to GitHub Pages](https://github.com/ericdevesh/devesh-properties/actions)** and re-run the latest failed run.

Future pushes to `main` that change `index.html`, `README.md`, or the Pages workflow deploy automatically.

## Prototype limitations
- Plot tiles are a schematic inventory finder, not an official surveyed/site plan.
- All 95 plot statuses default to **Pending**. Prices, areas, dimensions and facing directions stay blank until verified and entered.
- Broker changes and enquiries are stored in the current browser's local storage only. They do not sync between customer devices or to a broker.
- Do not use this prototype to represent title, regulatory approval, RERA status, exact plot boundaries, or confirmed availability.
- Before live commercial use, connect a secure API/database, authentication and broker roles, validated plot-plan geometry, and a broker notification channel. Verify property details against authorised documents.

## Files
- `index.html` — customer plot finder, broker local inventory editor, CSV import/export, and local enquiry register.
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow.
