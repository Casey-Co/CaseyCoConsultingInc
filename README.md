# Casey & Co. Consulting — website

The one-page website for **Casey & Co. Consulting Inc.**, built in the Debossed brand (midnight, champagne and ivory).

It is a plain static site: HTML and CSS with no build step, so GitHub Pages can host it for free.

## What's here

| Path | What it is |
| --- | --- |
| `index.html` | The website |
| `404.html` | "Page not found" page |
| `assets/css/styles.css` | All styles |
| `assets/img/` | Logo (SVG), ampersand, hero images, share image |
| `assets/icons/` | Favicon and app icons |
| `assets/fonts/` | Self-hosted Libre Caslon Display and Montserrat (SIL Open Font License) |
| `site.webmanifest`, `robots.txt`, `sitemap.xml` | Browser and search-engine files |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Preview with GitHub Pages

1. In this repository, go to **Settings › Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
3. After a minute or two the preview is live at `https://casey-co.github.io/CaseyCoConsultingInc/`.

## Launch on caseyco.ca (January)

Do this once the current site has moved off the domain:

1. **Verify the domain** (stops anyone else using it on GitHub Pages): your GitHub profile **Settings › Pages › Add a domain**, enter `caseyco.ca`, and add the TXT record GitHub gives you at your domain registrar.
2. **Point DNS at GitHub Pages** at your registrar:
   - `A` records for `caseyco.ca` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record for `www` → `casey-co.github.io`
3. **Connect the domain**: repository **Settings › Pages › Custom domain**, enter `caseyco.ca`, **Save** (GitHub adds a `CNAME` file to the repo).
4. Once the certificate is ready, tick **Enforce HTTPS**.

Check GitHub's current documentation before changing DNS, in case the addresses have changed.

## Editing

- Text lives in `index.html`. The contact email and phone appear in the Contact section and in the structured data in the `<head>`.
- Colours and type are defined at the top of `assets/css/styles.css`.

## Copyright

© Casey & Co. Consulting Inc. All rights reserved. The Casey & Co. name, logo, ampersand and site content may not be reused without permission. The fonts are used under the SIL Open Font License.
