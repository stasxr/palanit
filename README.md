# PALANIT

Personal-brand site for **PALANIT** — an independent cybersecurity studio.
Static site (plain HTML / CSS / JS), hosted on GitHub Pages at **https://palanit.com**.

## Structure

```
index.html    — the page
styles.css    — all styles (no build step)
script.js     — scroll-reveal animation
CNAME         — custom domain (palanit.com)
.nojekyll     — tells GitHub Pages to skip Jekyll
```

## Edit & deploy

1. Edit `index.html` / `styles.css`.
2. Commit and push to `main`:
   ```bash
   git add -A
   git commit -m "Update site"
   git push
   ```
3. GitHub Pages rebuilds automatically (~1 min).

## What to customise

- **Ventures section** — replace the placeholder project names, categories and
  card colours (`card__thumb--lime / pop / blue / ink`) with your real MVPs.
- **Stats section** — set real numbers.
- **Contact** — update the social links and `hello@palanit.com` if needed.

## DNS (Cloudflare)

`palanit.com` points to GitHub Pages. See deploy notes for the exact records.
