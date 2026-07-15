# cardscentral.github.io

The **landing page** for [Cards Central](https://github.com/cardscentral/cardscentral),
served at the org root: **https://cardscentral.github.io/**.

This repo is intentionally tiny — it contains only the static landing page and
is published **straight from the `main` branch** by GitHub Pages (Settings →
Pages → Source: *Deploy from a branch* → `main` / `(root)`). There is no build
step and no workflow: edit `index.html` / `styles.css` / `assets/`, push to
`main`, and it's live.

```
index.html    # the landing page (this IS the site root)
styles.css
assets/       # inline SVG artwork + icons
```

## The app lives elsewhere

The installable PWA is **not** in this repo. It is built and published by the
main app repo's own GitHub Pages site:

- Prod → https://cardscentral.github.io/cardscentral/app/
- QA   → https://cardscentral.github.io/cardscentral/qa/

Those deploy automatically from [`cardscentral/cardscentral`](https://github.com/cardscentral/cardscentral)
(see its `deploy-web.yml`). The landing page's "Open the app" links point at
`/cardscentral/app/`.
