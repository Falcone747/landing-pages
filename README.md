# Landing Pages

Two landing pages built with a shared dark-mode design system (Inter + Space Grotesk, mint `#68f7bb` accent, pure black backgrounds, glassy cards, gradient CTAs).

## Pip — AI Finance Copilot
[`pip-landing/index.html`](pip-landing/index.html) — SaaS landing for an AI finance assistant. 12 sections: sticky nav, hero with chat prompt, trusted-by row, 4-card features grid, 3-stat panel, automate section, 9-card testimonials, CTA banner, 2-tier pricing, comparison table, FAQ accordion, 3-card support, footer.

## EXIOR — Transformation Consultancy
[`exior-landing/index.html`](exior-landing/index.html) — Long-form landing for a transformation consultancy, using the same design system as Pip. Manifesto-style copy adapted into the same SaaS structure (hero, features, stats, automate, 11-bullet testimonials, CTA banner, two-tier pricing, comparison table, FAQ, support, footer).

## Run locally
Both files are self-contained — open `index.html` in any browser, or serve the folder:

```bash
cd pip-landing    && python3 -m http.server 8000
cd exior-landing  && python3 -m http.server 8001
```

## Shared design tokens
| Token | Value |
|---|---|
| Background | `#000000` |
| Foreground | `#ffffff` |
| Accent (mint) | `#68f7bb` → `#00a360` gradient |
| Secondary (blue) | `#0099ff` |
| Body font | Inter (400/500/600/700) |
| Display font | Space Grotesk (500/600/700) |
| Border radii | 12 / 18 / 24 px, pill 999 px |
| Borders | `rgba(255,255,255,0.1)` / `0.15` |
| Cards | `rgba(255,255,255,0.05)` on hover `0.07` |

Every component (nav, hero, prompt input, feature card, stat number, testimonial card with green opening quote, pricing plan with "Most Popular" badge, compare table with check/cross, FAQ plus icon, support card, footer) is implemented in the same way across both pages.
