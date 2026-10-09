# Marcus Market

Website for Marcus Market, a neighborhood grocer in Midtown Detroit (4614 2nd Ave).

It's a static site: `index.html` plus photos in `images/`. There's no build step.

## Going live

Every push to `main` deploys the site to GitHub Pages through `.github/workflows/pages.yml`.

One-time setup: in **Settings → Pages**, set **Source** to **GitHub Actions**.

## Adding the online shop link

When the online shop is ready, put its URL in `SHOP_URL` near the bottom of `index.html`. Until then, the Shop buttons show a "coming soon" message.
