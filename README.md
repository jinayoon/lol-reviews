# lol-match-analysis-pages

Static HTML for **sample / archived** League coaching reports. Split from [lol-match-analysis](https://github.com/jinayoon/lol-match-analysis) so the skill repo stays code + docs only.

## GitHub Pages

1. Create a **new** repository on GitHub (e.g. `lol-match-analysis-pages`).
2. From this folder:

   ```bash
   cd /path/to/lol-match-analysis-pages
   git init -b main
   git add .
   git commit -m "Initial Pages site from lol-match-analysis export"
   git remote add origin https://github.com/YOUR_USER/lol-match-analysis-pages.git
   git push -u origin main
   ```

3. In the new repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch `main` / folder `/ (root)`**.

Your site will be at `https://YOUR_USER.github.io/lol-match-analysis-pages/` (URLs match filenames, e.g. `sample-braum.html`).

## Updating reports

Add or replace `.html` (and optional `.md`) files in this repo and push. Do not commit personal reports you want private.

## Note

**Disable Pages** on [lol-match-analysis](https://github.com/jinayoon/lol-match-analysis) (Settings → Pages → None) so the old site stops serving broken links.
