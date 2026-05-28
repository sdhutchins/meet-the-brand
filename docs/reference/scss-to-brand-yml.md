# SCSS variables → `_brand.yml`

Mapping from your website SCSS to [`_brand.yml`](../../_brand.yml) ([brand.yml spec](https://posit-dev.github.io/brand-yml/)).

## Primary color

**`magenta-haze` — `#6A3D52`**

Set once at the top of `_brand.yml` as `color.primary: magenta-haze`. Tools map that to the navbar, headings, primary buttons, and other main accents. Everything else in the palette is supporting color.

## Typography

| SCSS | `_brand.yml` |
|------|----------------|
| `$fontBody` (IBM Plex Sans) | `typography.base` |
| `$fontSans` (Outfit) | `typography.headings.family` |
| `$fontMonospace` (Source Code Pro) | `typography.monospace` |

## Palette (supporting colors)

| SCSS | Hex | Role |
|------|-----|------|
| `$magenta-haze` | `#6A3D52` | **Primary** |
| `$fairy-tale` | `#C07E96` | Soft hover accent |
| `$puce` | `#B78899` | Warning / soft accent |
| `$rosy-amethyst` | `#915A70` | `success`, `info` |
| `$berkeley-blue` | `#2A5678` | `secondary`, links |
| `$hover-strong` | `#8A4F67` | `danger`, strong hover accent |
| `$dusty-rose` | `#C69CAA` | Mixed accent |
| `$soft-ivory` | `#F3ECE8` | Warm neutral surface |
| `$soft-cream` | `#FBF8F6` | Page `background` |
| `$charcoal-gray` | `#222A31` | `foreground` |
| `$soft-blue` | `#95AFC2` | Technical soft accent |
| `$dusty-sky` | `#9FB1BF` | Technical pale accent |
| `$gama` | `#616B76` | Muted text token |
| `$lightgray` | `#7A838C` | Secondary text; `tertiary` |
| `$delta` | `#915A70` | Accent alias |
| `$epsilon` | `#F1EBE7` | Borders, dividers |
| `$white` | `#FFFFFF` | High-contrast light text |

For a white page instead of soft-cream: `color.background: white` and `defaults.bootstrap.defaults.body-bg: $brand-white`.

## Using the brand file

```bash
cp _brand.yml /path/to/your-project/
```
