# lol-reviews

Static HTML for **sample / archived** League coaching reports. Split from [analyze-lol-match](https://github.com/jinayoon/analyze-lol-match) so the skill repo stays code + docs only.

## GitHub Pages

1. Create a **new** repository on GitHub named **`lol-reviews`** (or rename an existing Pages repo to that name in **Settings → General → Repository name** — the site URL becomes `https://YOUR_USER.github.io/lol-reviews/`).
2. From this folder:

   ```bash
   cd /path/to/lol-reviews
   git init -b main
   git add .
   git commit -m "Initial Pages site from analyze-lol-match export"
   git remote add origin https://github.com/YOUR_USER/lol-reviews.git
   git push -u origin main
   ```

3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch `main` / folder `/ (root)`**.

Your site will be at `https://YOUR_USER.github.io/lol-reviews/` (URLs match filenames, e.g. `sample-braum.html`).

If you already pushed under another repo name, rename the repo on GitHub (above) and update the remote:

```bash
git remote set-url origin https://github.com/YOUR_USER/lol-reviews.git
```

## Updating reports

Add or replace `.html` (and optional `.md`) files in this repo and push. Do not commit personal reports you want private.

## Note

**Disable Pages** on [analyze-lol-match](https://github.com/jinayoon/analyze-lol-match) (Settings → Pages → None) so the old site stops serving broken links.
