# argusslabs.com

The Arguss Labs marketing site, served by GitHub Pages at https://www.argusslabs.com.

Plain static HTML and CSS, with no build step. Edit the files and push to `main`;
Pages publishes within a minute or two.

| File | Page |
|---|---|
| `index.html` | `/` |
| `business-brain.html` | `/business-brain` (Pages serves `.html` files without the extension) |
| `404.html` | any unknown path |
| `assets/site.css` | the site's compiled Tailwind stylesheet |
| `assets/logo.webp`, `assets/logo-a.webp` | logos (`logo.webp` is also the social-card image) |
| `CNAME` | the custom domain; keep it |
| `.nojekyll` | tells Pages to publish the files as they are |

If you add a page, also add it to `sitemap.xml`.

## History

Rebuilt on 2026-11-16 from the server-rendered output of the Ploy-hosted Astro site.
The Ploy analytics, experiment scripts, store-cart widget and React hydration bundles were removed.
The pages have no interactive parts, so they render the same without them.
The `ploy-*` names in the CSS classes are only design-token names left from that build.
