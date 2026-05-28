# docs

Quarto website that previews [`_brand.yml`](../_brand.yml), plus reference notes.

## Preview locally

```bash
cd docs && quarto preview
```

## Deploy (GitHub Pages)

Pushes to `main` run [`.github/workflows/publish-docs.yml`](../.github/workflows/publish-docs.yml), which renders this folder and publishes `_site` to GitHub Pages.

In the repo **Settings → Pages**, set **Source** to **GitHub Actions**.

## Reference

| File | Description |
|------|-------------|
| [reference/scss-to-brand-yml.md](reference/scss-to-brand-yml.md) | SCSS variable mapping (not part of the Quarto site) |

## Site pages

| Page | Source |
|------|--------|
| Home | `index.qmd` |
| Components | `components.qmd` |
