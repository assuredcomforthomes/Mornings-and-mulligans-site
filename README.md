# Mornings & Mulligans — direct booking site

Static site for the golf-included vacation rental on Callawassie Island, SC.
Deployed via Cloudflare Pages (git-connected) to `morningsandmulligans.com`.

## Structure
Plain static HTML/CSS/images at the repo root — no build step. Cloudflare
Pages serves this repo directly (build command: none, output directory: `/`).

- `index.html` — homepage
- `hilton-head-golf-vacation-rental/`, `beaufort-sc-vacation-rental/`, `parris-island-graduation-lodging/` — SEO landing pages
- `css/style.css` — stylesheet
- `img/` — photos (WebP) and social-share image
- `_headers`, `robots.txt`, `sitemap.xml`, `favicon*` — site plumbing

## Updating the site
Edit files directly and push to `main`. Cloudflare Pages redeploys
automatically within a minute or two of a push.
