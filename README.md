# Meet the Brand

My personal [brand.yml](https://posit-dev.github.io/brand-yml/) theme for Quarto, Shiny, bslib, and related tools.

- **`_brand.yml`** — **primary: magenta-haze** (`#6A3D52`), supporting editorial rose/blue palette with higher-contrast neutrals and accents, typography (IBM Plex Sans, Outfit, Source Code Pro).
- **`_brand-alt.yml`** — alternate brand.yml variant when I want a different brand treatment from the primary file.
- **`docs/`** — Quarto preview site for `_brand.yml` (deployed via GitHub Pages).

Copy `_brand.yml` into any project root that supports brand.yml theming.

## Viewing the brand site

```bash
cd docs && quarto preview
```

This repo holds brand.yml and related assets for personal website and documentation projects.

## Directory Structure

```plaintext
.
├── .github/                            # Issue templates, pull request template, and CI/docs workflows
├── CONTRIBUTING.md                     # Contribution guidance for this repo
├── LICENSE                             # Project license
├── README.md                           # Project overview
├── _brand.yml                          # Primary brand.yml theme
├── _brand-alt.yml                      # Alternate brand variant
├── docs/                               # Quarto preview site and reference documentation
├── examples/                           # Minimal example outputs
└── docs/reference/scss-to-brand-yml.md # SCSS token to brand.yml mapping reference
```
