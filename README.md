# Landing Pages

Static HTML landing pages and sales pages, all self-contained (no build step).

## Pip — AI Finance Copilot (Penny-inspired)
[`pip-landing/index.html`](pip-landing/index.html) — 12-section SaaS landing, dark theme with mint `#68f7bb` + blue `#0099ff` accents, Inter + Space Grotesk.

## EXIOR — Marketing Landing (Orbai-inspired)
[`exior-landing/index.html`](exior-landing/index.html) — 12-section landing for the tech-intermediation consultancy, light `#f5f5f5` + blue/purple accents, Inter + Satoshi.

## EXIOR — Marketing Landing v3 (dark + gradient + ultra-ergonomic)
Same file as above, latest version. Dark `#050507` background, electric blue `#0099ff` + purple `#814fff` gradient system, WCAG AAA contrast (16.4:1), touch targets ≥ 48px, `prefers-reduced-motion` strict, focus rings visible, skip-to-content link, semantic ARIA.

## EXIOR — Sales Page (commercial conversion)
[`exior-sales/index.html`](exior-sales/index.html) — Complete sales page for the 1 000 € HT custom analysis product. Structure follows the brief: rupture → reconnaissance → contrefactuel → produit → démo de livrable → process → objections → CTA. Three switchable hero angles via tabs. Slogan: "Réinventez l'entreprise." Single primary CTA: "Commander l'analyse · 1 000 € HT".

## Run locally
Each `index.html` is self-contained — open in a browser, or serve the folder:

```bash
cd <folder> && python3 -m http.server 8000
```

## Hosting
Live URLs (via cloudflared quick-tunnels):
- pip-landing: served on port 8765
- exior-landing: served on port 8766
- exior-sales: served on port 8768
