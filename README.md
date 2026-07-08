# Aflossingstabel — steefware.com

Mortgage / loan repayment calculator. Annuity math (Belgian effective-annual → monthly rate convention), CAP/FLOOR for variable rates, monthly and yearly amortization tables, CSV export. Full EN/NL toggle.

**▶ Use it: https://www.steefware.com/aflossingstabel/**

Read how it works: [Aflossingstabel berekenen: zo werkt je maandbedrag](https://www.steefware.com/blog/aflossingstabel-berekenen.html) (NL)

No cookies, no ads, no accounts — everything runs locally in your browser. Part of [steefware.com](https://www.steefware.com/). If it saved you some time: [☕ buy me a coffee](https://ko-fi.com/steefware).

Single self-contained `index.html` (Tailwind via CDN, vanilla JS) — no build step, same setup as the other steefware apps.

## Local development
Open `index.html` in a browser, or serve the folder:
```bash
python -m http.server
```

## Deployment (GitHub Pages)
`.github/workflows/deploy.yml` publishes the repo root to Pages on pushes to `main`.
