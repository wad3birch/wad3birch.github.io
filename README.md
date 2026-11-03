# Han Bao — Academic Homepage

Source for [wad3birch.github.io](https://wad3birch.github.io), built with [Astro](https://astro.build).

## Development

```bash
cd astro-website
pnpm install
pnpm dev      # http://localhost:4321
pnpm build    # outputs to astro-website/dist
```

## Structure

```
astro-website/
├── public/favicon.svg
├── src/
│   ├── assets/              # Portrait and logos (optimized at build time)
│   ├── components/Chapter.astro # Numbered section shell (§ I, § II …) with sticky rail
│   ├── layouts/Layout.astro # <head>, SEO metadata, theme tokens (light/dark), page grid
│   └── pages/index.astro    # Page content: publications, research areas, awards and service are data arrays at the top
└── astro.config.mjs
```

## CV

`cv.tex` is compiled to `/cv.pdf` during deployment. To preview it locally:

```bash
tectonic -o astro-website/public cv.tex
```

## Deployment

Pushing to `main` runs `.github/workflows/deploy.yml`, which compiles the CV, builds the site and publishes `astro-website/dist` to GitHub Pages.
