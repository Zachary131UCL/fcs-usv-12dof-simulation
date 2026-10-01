# Deployment notes

This directory is intentionally separate from the research workspace so that only approved public material is uploaded.

## GitHub Pages configuration

- Repository visibility: public
- Default branch: `main`
- Pages source: GitHub Actions
- Public entry point: `index.html`
- HTTPS: enabled by GitHub Pages

The workflow in `.github/workflows/pages.yml` publishes the directory whenever `main` is updated. It can also be run manually from the repository's **Actions** tab.

## Optional custom domain

The default `github.io` address requires no domain purchase. If a custom domain is added later, configure it under **Settings → Pages → Custom domain** and keep HTTPS enforcement enabled.
