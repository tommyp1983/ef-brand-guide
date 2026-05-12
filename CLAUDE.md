# Exit Forward Brand Guide

Static HTML site deployed to [brand.exitforward.com.au](https://brand.exitforward.com.au) via Vercel.

## Structure

- `index.html` — the entire site (all content, CSS and JS inline)
- `assets/` — photos and SVGs (logo, icons, photography)
- `fonts/` — local woff2 files (Bebas Neue, Inter, Minion Pro)
- `vercel.json` — Vercel config (cleanUrls, no trailing slash)
- `robots.txt` — noindex while site is in draft

## Deployment

Push to `master` → Vercel auto-deploys.

```
git add -A && git commit -m "message" && git push
```

GitHub: https://github.com/tommyp1983/ef-brand-guide

## Brand rules (apply to all edits)

- Black `#000` and white `#FFF` only — no greys, no accent colours
- Bebas Neue for all headings (uppercase)
- Inter for all body copy (sentence case)
- Minion Pro italic for taglines and pull-quotes only
- No emoji. No rounded corners. No shadows.
- Forward arrow `→` is the list marker and CTA suffix
- Voice: calm, confident, operator-led. Avoid hype, urgency, consulting clichés.
