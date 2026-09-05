# ÉCLAT asset audit

## Pipeline status

- Repository: `Senthan-X/boutique-and-fashion-templates`
- Working branch: `eclat-development`
- Template entry point: `eclat-index.html`
- Current phase: verified-image catalog manifest

## Source inventory

| Archive | Entries | Internal prefix |
| --- | ---: | --- |
| clothing.zip | 251 | CLO |
| soles.zip | 443 | SOL |
| luxury.zip | 557 | LUX |
| accessories.zip | 403 | ACC |
| **Total archive entries** | **1,654** | |
| **Extracted image files** | **1,651** | |

Five duplicate-content groups were detected during checksum analysis.

## Binding curation rules

1. Inspect each image visually before customer-facing naming.
2. Classify it as Product, Drop, Set, Look, Editorial, or Reject.
3. Prioritize unbranded and brand-neutral products throughout the primary experience.
4. Keep recognizable branded imagery only as a secondary mix inside the main catalog.
5. Exclude screenshots, social-media captures, watermarked assets, store-signage imagery, and unsuitable content.
6. Preserve useful multi-product compositions for Drops, Sets, and Looks.
7. Verify department and product type before creating the final display name.
8. Convert approved assets to WebP and embed them as Base64 in the final self-contained HTML.

## Visual direction

ÉCLAT is Boutique & Fashion Version 3: a bold, kinetic, typography-led fashion publication × storefront, visually distinct from Maison and Atelier.

## Required delivery characteristics

- One self-contained HTML file
- Internal CSS and JavaScript
- No required third-party dependencies
- System-responsive light/dark theme plus explicit override
- Seven-language i18n: EN, ES, FR, DE, PT, AR with RTL, and ZH
- Browser-language detection through `navigator.language`
- Heavy, verified catalog
- Cart icon with item count
- Scroll-triggered animated view transitions
- Senthan & Co authorship and credit
