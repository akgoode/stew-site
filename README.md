# stew-site

The public one-page site for [Stew](https://github.com/akgoode/stew), the
home binder app. Serves the three URLs App Store Connect requires:

- **Marketing:** `/` — the page itself
- **Privacy policy:** `/#privacy`
- **Support:** `/#support`

Plain static HTML, no build step. Served by GitHub Pages from the `main`
branch root. Edit `index.html` and push to publish.

Policy changes must update the effective date in the Privacy Policy
section.
