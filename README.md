# Junming Ren — Personal Website

This repository contains the source for my personal website and résumé. The website is a standalone static site deployed with GitHub Pages; this README is not used as the homepage.

## Local preview

Open `index.html` directly, or run a small static server from this directory:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

Push the repository to a GitHub repository whose default branch is `main`. In **Settings → Pages**, set **Source** to **GitHub Actions**. The included workflow will deploy the site after every push to `main`.
