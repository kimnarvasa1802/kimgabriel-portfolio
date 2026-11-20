# Kim Gabriel portfolio

Static portfolio site for Kim Gabriel (Gabriel Kim Narvasa), a Shopify and WordPress developer.
Live site: https://kimgabriel.pages.dev

## How it works
- Plain HTML, CSS and a little JavaScript. There is no build step.
- Hosted on Cloudflare Pages. Pushing to `main` deploys the site automatically.

## Files
| File | What it is |
|---|---|
| `index.html` | Home page |
| `work.html` | All work (served at `/work`) |
| `404.html` | Not-found page |
| `img/` | Project screenshots, photo and share image |
| `_headers` | Cloudflare security and cache headers |
| `robots.txt`, `sitemap.xml`, `llms.txt` | Search and AI-search files |

## Editing
Project cards on the home and work pages are plain HTML, so edit them directly.
Update the FAQ text in the page and in its JSON-LD block together so they match.

## Preview locally
Run `python -m http.server 8000` in this folder, then open http://localhost:8000
