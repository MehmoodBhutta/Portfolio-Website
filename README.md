# Workflowry - Portfolio Website

Single-file static portfolio for **Workflowry** (Mehmood Bhutta): n8n, Python and LLM automation engineering.

## Live site

Once GitHub Pages is enabled, the site is served at:
https://mehmoodbhutta.github.io/Portfolio-Website/

## Run locally

```bash
python3 -m http.server 8765
# open http://localhost:8765
```

Any static file server works. No build step, no dependencies.

## Structure

- `index.html` - the entire site (HTML + CSS + JS, no frameworks)
- `robots.txt` / `sitemap.xml` - for search indexing once hosted
- GitHub Pages serves it directly from `main`

## Features

- Dark tech theme, emerald accent, animated logo/hero (particles, aurora, terminal typing)
- Live repo freshness badges pulled from the GitHub API at page load
- Project cards, case studies, stack, process, contact (mailto-based form)
- Full SEO: Open Graph, Twitter card, JSON-LD structured data, canonical URL
- `prefers-reduced-motion` support throughout
- Upwork link placeholder (update `id="upworkLink"` href when the profile URL is ready)

## TODO before launch

- [ ] Replace `https://www.upwork.com/` with the real Upwork profile URL (search for `upworkLink`)
- [ ] Replace `hello@workflowry.com` if a different real inbox is wanted
- [ ] Enable GitHub Pages (Settings > Pages > deploy from branch `main`, root)
