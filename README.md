# FA Technest agency portfolio

This is a static, single-page portfolio site. The deployment entry point is `index.html`; its Tailwind browser runtime is bundled in `tailwind-browser.js`, so the page does not request styling code, fonts, or photos from a third-party host.

## Deploy

Publish `index.html` and `tailwind-browser.js` together to any static web host, such as GitHub Pages, Netlify, or Cloudflare Pages. No build step or package installation is required.

The contact form validates the submission in the browser and opens the visitor's email app with a prefilled message to `hello@fatechnest.com`. Update that address and the social profile links in `index.html` before publishing if they differ from the agency's live contact details.
