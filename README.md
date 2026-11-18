# All Pro Collision website

Static site, no build step. Open `index.html` or deploy the folder to any static host
(Cloudflare Pages, Netlify, GitHub Pages).

- `index.html` – public site (SEO meta, AutoBodyShop + FAQPage structured data)
- `styles.css`, `assets/` – shared styles, logos
- `robots.txt`, `sitemap.xml`, `llms.txt` – crawler and AI-search files

## Before launch
0. The site is currently set to no-index for previewing. Undo the two `PREVIEW` notes in `index.html` and `robots.txt`.
1. Phone, address and email come from the owner's email signature. Still to confirm (search `TODO-NAP`):
   hours and the domain `allprocollisionatl.com`. All details must match the Google Business Profile exactly.
2. Confirm the claims in the copy: free estimates, all insurers, the six services, hours.
3. Add before/after photos (instructions in the `PHOTOS` comment in `index.html`).
4. Set `FORM_ENDPOINT` at the bottom of `index.html` so estimate requests are delivered without
   opening the visitor's email app.
