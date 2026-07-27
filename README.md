# Valerio Li — Portfolio Site

Static portfolio for Valerio Li, published at https://valerioli.vercel.app/.

The site is intentionally simple: plain HTML/CSS/JS, no build step, and Vercel serves it directly from GitHub.

## Structure

```
portfolio-site/
├─ index.html              # homepage
├─ ainfinity-social.html   # AInfinity social automation case study
├─ kol-radar.html          # AI Creator Radar demo page
├─ writings.html           # writing index
├─ vercel.json             # static routing config
└─ assets/images/videos    # local media used by the site
```

## Local Preview

From this folder:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/.

## Deploy

The GitHub repository is `valerioli/portfolio-site`. Push changes to `main`; Vercel redeploys automatically.

```bash
git status
git add index.html ainfinity-social.html README.md
git commit -m "Update portfolio"
git push origin main
```

## Editing Notes

Keep the site lightweight and editorial. Major work should appear on the homepage first, then link to a focused detail page when the project needs context, proof points, or an interactive demo.
