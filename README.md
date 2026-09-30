# Senthan & Co — Boutique & Fashion Templates

A collection of eight self-contained storefront demos by Senthan & Co. Each template is a standalone HTML page with embedded imagery and inline CSS and JavaScript. The pages have no external runtime dependencies or build step.

## Templates

| Template | Direction | File |
|---|---|---|
| ReSole | Verified sneaker resale | [resole.html](resole.html) |
| Maison Rue | Quiet luxury ready-to-wear | [maisonrue.html](maisonrue.html) |
| Bale Yard | Graded wholesale bales | [baleyard.html](baleyard.html) |
| Street Fix Co | Small-run streetwear | [streetfixco.html](streetfixco.html) |
| Second Thread | Vintage and secondhand | [secondthread.html](secondthread.html) |
| Maison | Editorial fashion commerce | [maison-index.html](maison-index.html) |
| Atelier | Product-led luxury and studio imagery | [atelier-index.html](atelier-index.html) |
| ÉCLAT | Contemporary, catalogue-first fashion | [eclat-index.html](eclat-index.html) |

The root [index.html](index.html) is the collection landing page. It links to all eight demos and includes light/dark themes and language switching. The templates support English, Spanish, French, German, Portuguese, Arabic with RTL, Chinese, and Swahili.

## Preview and publishing

The GitHub Pages workflow is [`.github/workflows/pages.yml`](.github/workflows/pages.yml). It deploys the repository root on pushes to `main` and can also be started manually from GitHub Actions. When Pages is enabled for this repository, the collection landing page is served at:

`https://senthan-x.github.io/boutique-and-fashion-templates/`

Each template is available at its filename under that base URL, for example `/maison-index.html`.

## Structure

- `index.html` — collection landing page
- `*-index.html` and the named `.html` files above — standalone storefront demos
- `previews/` — preview materials
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow

## Credits

Original templates by **Senthan & Co**. Contact information shown in demos is fictional sample data for East African locations.
