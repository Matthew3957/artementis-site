# artementis.com

Public deploy repo for the Arte Mentis site, served by GitHub Pages
(deploy from branch: `main`, `/ (root)`) at https://artementis.com.

- `index.html`, `services.html`, `work.html`, `about.html`, `contact.html`,
  `privacy.html`, `terms.html` — the site. No build step, no frameworks, no scripts.
- `styles.css` — shared styles; each page adds a small page-specific `<style>` block.
- `404.html` — standalone not-found page in the same style.
- `sitemap.xml`, `robots.txt` — indexing.
- `favicon.svg` — mark in the brand accent (#B5543B).
- `CNAME` — custom domain for GitHub Pages.

**This repo is a deploy target, not the source of truth.** The site is authored
in a separate private repo; edits land there first and are copied here. Don't
edit here directly.
