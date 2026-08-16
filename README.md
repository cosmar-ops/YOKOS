# YOKOS

Phase 1 static site for a direct-to-consumer sleep supplement brand. Radical honesty: evidence grades on everything, study links on every claim, batch lab certificates public.

## What is here

- `index.html` - home: the stack, grade legend, "who this is not for"
- `magnesium.html`, `glycine.html`, `theanine.html`, `tart-cherry.html`, `apigenin.html` - product pages
- `evidence.html` - the grading rules (A / B / C+ / C) and current grades
- `lab.html` - batch certificate placeholders

## Phase 1 rules baked in

- Plain HTML + Tailwind via CDN. No build tools, no frameworks, no databases.
- Brand name is the placeholder `BRAND` in every page. Find-and-replace with the real name when ready.
- Buy buttons link to `#checkout` placeholders. No payment, checkout, subscription or tax code in any phase.
- The FDA disclaimer appears verbatim in every footer.

## How to view it live

GitHub Pages, from your phone: repo Settings > Pages > Source: Deploy from a branch > Branch: `main`, folder `/ (root)` > Save. After about a minute the site is at `https://<username>.github.io/YOKOS/`.
