# Джулия Тодорова — локален сайт

Static Bulgarian landing page for localhost review.

## Run locally

```bash
cd julia-todorova-site
python3 -m http.server 5173
```

Open: http://localhost:5173

## Deployment

- Live URL: https://www.juliatodorova.bg/
- Canonical URL, sitemap, robots, Open Graph, Twitter preview tags, and JSON-LD schema point to the live `www` domain because the apex domain redirects there.
- If the primary domain changes later, update `index.html`, `robots.txt`, `sitemap.xml`, and schema URLs to the final 200 URL.
- Confirm final working days/hours and whether weekend appointments should be shown.
