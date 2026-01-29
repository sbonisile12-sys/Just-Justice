# Just Justice – GitHub Pages Site

This repository is ready to be published via **GitHub Pages**.

## Structure
- `index.html`, `styles.css`, `script.js`, `site.webmanifest`
- `assets/` — logos, favicons, platform icons, social cards, crest.svg
- `.nojekyll` — disables Jekyll so assets in nested folders are served as-is

## Publish to GitHub Pages
1. Create a new GitHub repository and upload these files.
2. Go to **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: **main** and folder **/** (root)
3. Save. Your site will be available shortly at `https://<your-username>.github.io/<repo-name>/`.

## Optional: GitHub Actions (CI deploy)
If you prefer CI, add a workflow under `.github/workflows/pages.yml` with an actions deploy (not included here to keep the zip minimal).
