# Universal Solutions website

Static site for universalsolutions.in — ground transportation operations support.

## Structure
- `index.html` — homepage
- `about.html`, `case-studies.html`, `contact.html`
- `services/` — services overview + 4 detail pages
- `css/style.css`, `js/main.js`
- `images/` — logo, hero video, poster
- `CNAME` — custom domain for GitHub Pages

## Deploy via GitHub Pages
1. Push this folder's contents to the root of your GitHub repo (e.g. `main` branch).
2. In the repo: Settings → Pages → Source: `Deploy from a branch`, Branch: `main` / `root`.
3. Settings → Pages → Custom domain: enter `universalsolutions.in`, save (this writes/confirms the CNAME file).
4. At your domain registrar, add DNS records pointing to GitHub Pages:
   - A records for `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME record for `www` → `<yourusername>.github.io`
5. Wait for DNS to propagate, then enable "Enforce HTTPS" in Pages settings.
