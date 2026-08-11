# Booze & Barrels — static site

## Structure

    index.html            Landing page
    product-detail.html   Product detail page
    assets/support.js     Runtime that renders both pages
    images/               Product photography (5 files)

## Hosting on GitHub Pages

1. Copy the contents of this folder to the root of your repository (or into `/docs`).
2. Settings → Pages → Source: **Deploy from a branch**, pick the branch and `/ (root)` or `/docs`.
3. `index.html` is served automatically; the product page is at `/product-detail.html`.

Keep the folder structure as-is — the pages reference `./assets/support.js` and `./images/*` by relative path.

## Notes

- The pages need an internet connection on first load (the runtime and the two Google fonts load from a CDN).
- For a fully offline copy, use the self-contained single files in `bundle/` instead.
- Photography is placeholder-grade product imagery; replace files in `images/` with the same names to swap them in.
