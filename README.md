# Aflossingstabel — steefware.com

Mortgage / loan repayment calculator. Annuity math (Belgian effective-annual → monthly rate convention), CAP/FLOOR for variable rates, monthly and yearly amortization tables, CSV export. Full EN/NL toggle.

Single self-contained `index.html` (Tailwind via CDN, vanilla JS) — no build step, same setup as the other steefware apps.

## Local development
Open `index.html` in a browser, or serve the folder:
```bash
python -m http.server
```

## Deployment (GitHub Pages)
`.github/workflows/deploy.yml` publishes the repo root to Pages on pushes to `main`.
