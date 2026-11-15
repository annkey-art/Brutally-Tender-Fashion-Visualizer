# Brutally Tender Fashion Visualizer

A five-category fashion try-on demonstrator for exploring silhouettes, cuts, and outfit combinations. The existing curtain visualizer and cake visualizer are separate projects.

## Add new clothes without changing code

1. Open this repository on GitHub.
2. Open **gallery → overlays**.
3. Choose one folder: **Dress**, **Shirt**, **Trousers**, **Skirt**, or **Jacket**.
4. Choose **Add file → Upload files**. Upload your cropped transparent PNG or WebP garment images, then **Commit changes** to the **main** branch.
5. The GitHub Action **Update Fashion Catalog** automatically refreshes `fashion-data.js`. The published GitHub Pages site may take a few minutes to update; refresh the browser when ready.

You do **not** need to edit `index.html` or `fashion-data.js` manually when adding garments. If new items do not appear, check the **Actions** tab for any failed workflow run.

## Current contents

- Dress: waiting for overlays
- Shirt: waiting for overlays
- Trousers: waiting for overlays
- Skirt: 5 overlays
- Jacket: 5 overlays

## Testing

1. Choose an EU size (style preference only; no real brand size lookup yet).
2. Upload a front-facing photo. It remains in the browser.
3. Choose **Skirt** and try one image; choose **Jacket** and try another.
4. Move/resize layers, then click **Save look as PNG**.

## Future extension

Links to 3–5 similar in-stock products, retailer catalog integration, accurate sizing per brand, more categories, accessories and menswear are planned but are **not** live features. PNG overlays do not guarantee actual fit.

## Recovery

Original code and images are preserved in branch **backup-before-fashion-launch-2026-11-15**.
