# Thai Bites — Final Site Package

Drag-and-drop these files into your repo root on GitHub (Code → Add file → Upload files). **Upload the files themselves, not this zip.**

## Files
- `index.html` — Home page
- `menu.html` — Menu page (Mains + Sides populated)
- `contact.html` — Contact page
- `styles.css` — Minimal global CSS (optional; safe to keep)
- `css/menu-page.css` — Scoped menu styles
- `assets/logo.svg` — Placeholder logo
- `.github/workflows/deploy-pages.yml` — (optional) GitHub Pages via Actions
- `.nojekyll` — (optional) Required by some setups
- `404.html` — Not found page

## Publish via GitHub Pages
### Option A — GitHub Actions (recommended)
1. Keep `.github/workflows/deploy-pages.yml` in the repo.
2. In **Settings → Pages → Build and deployment**, set **Source = GitHub Actions**.
3. Push to `main`. The **Deploy static site to GitHub Pages** workflow will publish your site.

### Option B — From Branch
1. Delete `.github/workflows/deploy-pages.yml` if present (optional).
2. In **Settings → Pages**, set **Source = main** and **Folder = / (root)**.
3. Open the URL GitHub shows (usually `https://<user>.github.io/<repo>/`).

