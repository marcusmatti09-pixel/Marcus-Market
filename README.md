# Marcus Market

Website for Marcus Market, a neighborhood grocer in Midtown Detroit (4614 2nd Ave).

It's a static site: `index.html` plus photos in `images/`. There's no build step.

## Going live

GitHub Pages publishes the site straight from the `main` branch (**Settings → Pages → Deploy from a branch → main, / (root)**). Anything pushed to `main` goes live within a minute or two.

The site is served at **marcusmarket.com** (set by the `CNAME` file). The domain's DNS is managed in Squarespace.

## Adding the online shop link

When the online shop is ready, put its URL in `SHOP_URL` near the bottom of `index.html`. Until then, the Shop buttons show a "coming soon" message.

## Job applications

`apply.html` is the application form. Submissions go through Web3Forms (web3forms.com), which emails each one to the hiring inbox without the address appearing on the site. Put the Web3Forms access key in `ACCESS_KEY` in `apply.html`, and set `APPLY_URL` in `index.html` to `/apply.html` so the Apply Now button opens the form.
