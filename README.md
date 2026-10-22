# Julieta Diaz | MSDM Portfolio

A Quarto website built for IBM 6500 (M10: Sharing Outputs with the Audience).

**Live site:** https://jukedz.github.io/msdm-portfolio/

## Pages

| File | Page |
|------|------|
| `index.qmd` | Home: bio, photo, career aspirations, skills, and education |
| `cep-dashboard.qmd` | Portal to the CEP dashboard |
| `farm-store-dashboard.qmd` | Quarto dashboard (`format: dashboard`) built with GA4 sample data |
| `css-scss.qmd` | How this site is styled with CSS and SCSS |
| `listings.qmd` | Quarto listings, filled from `projects.yml` |

## Other files

- `_quarto.yml`: site structure, navbar, and theme
- `styles/theme.scss` and `styles/extras.css`: custom styling
- `data/ga4_channel_funnel.csv`: GA4 sample data queried in BigQuery
- `docs/`: the rendered website served by GitHub Pages

## Render

Open this folder in Positron or RStudio and run `quarto render` in the Terminal.
