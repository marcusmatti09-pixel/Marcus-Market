# Marcus Market

Website for Marcus Market, a neighborhood grocer in Midtown Detroit (4614 2nd Ave).

It's a static site: `index.html` plus photos in `images/`. There's no build step.

## Going live

GitHub Pages publishes the site straight from the `main` branch (**Settings → Pages → Deploy from a branch → main, / (root)**). Anything pushed to `main` goes live within a minute or two.

The site is served at **marcusmarket.com** (set by the `CNAME` file). The domain's DNS is managed in Squarespace.

## Adding the online shop link

When the online shop is ready, put its URL in `SHOP_URL` near the bottom of `index.html`. Until then, the Shop buttons show a "coming soon" message.

## Job applications

Apply Now opens `apply.html`, a short application form. Submissions are emailed to the hiring inbox in `SEND_TO` (in `apply.html`) through FormSubmit (formsubmit.co). The address is stored in two pieces so spam bots scanning the page don't pick it up. Applicants can attach a resume (PDF, Word or photo, up to 5 MB). The first submission to a new address sends an activation email that has to be confirmed once.
