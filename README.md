# Personal Academic Website — Kazuya Masuda

Built with [Quarto](https://quarto.org) and deployed via GitHub Pages.

## Local preview

```bash
quarto preview
```

## Render

```bash
quarto render
```

## Deploy to GitHub Pages

1. Create a new GitHub repo and push this directory.
2. In the repo, run once locally to create the `gh-pages` branch:
   ```bash
   quarto publish gh-pages
   ```
3. In **Settings → Pages**, set source to the `gh-pages` branch.
4. Update `site-url` in `_quarto.yml` (replace `USERNAME` and `REPO`).
5. After the initial setup, pushes to `main` auto-deploy via the
   GitHub Actions workflow in `.github/workflows/publish.yml`.

## Files

- `_quarto.yml` — site config and navbar
- `styles.css` — minimal styling (white background, serif body)
- `index.qmd`, `research.qmd`, `teaching.qmd`, `cv.qmd`, `contact.qmd` — pages
