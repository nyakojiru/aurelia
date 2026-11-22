# aurelia

Publishes aurelia.jirulabs.com. This repo holds no artwork: the content lives in a private
repo, and `.github/workflows/pages.yml` builds it with [trazos](https://github.com/nyakojiru/trazos)
(its reusable `site` workflow, read-only deploy key in the `CONTENT_KEY` secret) and publishes
it on GitHub Pages. It runs when the content asks for it, or by hand.
