# Elevations Design Build — website

A single-page marketing site for Elevations Design Build (residential design-build, North County San Diego). Plain HTML + assets, no build step. Designed to host free on **GitHub Pages**.

## Files
- `index.html` — the whole site.
- `assets/` — logo, project photos.
- `assets/video/` — hero loop + transformation reel (self-hosted MP4s).
- `.nojekyll` — tells GitHub Pages to serve files as-is.

## Preview locally
From this folder:
```
python3 -m http.server 8000
```
Then open http://localhost:8000 in a browser.

## Put it live on GitHub Pages (no coding)
1. Create a free account at https://github.com/signup
2. Create a new repository (green **New** button): name it `elevations-site`, set **Public**, don't add a README.
3. On the empty repo page, click **uploading an existing file** and drag in everything inside this folder (the `index.html`, the `assets` folder, and `.nojekyll`). Commit.
4. Go to **Settings → Pages**. Under **Build and deployment**, set Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**. Save.
5. Wait ~1 minute. Your site is live at `https://<your-username>.github.io/elevations-site/`.

## Still to add (real info)
Phone, email, contractor license #, real client reviews, and social links. Search `index.html` for "To be added" and the `Follow`/contact sections.

## Custom domain (later)
A domain like `elevationsdesignbuild.com` can be pointed at GitHub Pages via **Settings → Pages → Custom domain** plus a DNS change at the registrar.
