# Tong Shen — Personal Website

Academic website based on [tongshen01/tongshen01.github.io](https://github.com/tongshen01/tongshen01.github.io) and the Hugo Academic / Wowchemy theme. The original portrait and academic layout are retained; content is based on the supplied September 2026 CV.

Live site: https://vacuumfreezer.github.io/

## Edit content

- `content/authors/admin/_index.md`: biography, education, social links
- `content/_index.md`: research, employment, skills, conferences, awards, contact
- `content/publication/`: publications and citations
- `config/_default/menus.yaml`: navigation
- `assets/scss/custom.scss`: layout refinements

## Build locally

Use Hugo **extended 0.111.3** and Go 1.20 or later. This Hugo version is pinned for compatibility with the original Wowchemy v5 template.

```sh
hugo server --disableFastRender
hugo --gc --minify
```

GitHub Pages deployment uses `.github/workflows/gh-pages.yml`. In repository Settings → Pages, select **GitHub Actions** as the source. Pushes to `main` build and publish the site; pull requests only build it.

The template's MIT license is preserved in `LICENSE.md`.

The full resume PDF is intentionally not published. Contact links use the academic email, GitHub, and LinkedIn.
