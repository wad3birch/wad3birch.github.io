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
│   ├── assets/              # Portrait, logos, paper figures (optimized at build time)
│   ├── layouts/Layout.astro # <head>, SEO/social metadata, global styles
│   └── pages/index.astro    # Page content: publications and research areas are data arrays at the top
└── astro.config.mjs
```

## Deployment

Pushing to `main` runs `.github/workflows/deploy.yml`, which builds the site and publishes `astro-website/dist` to GitHub Pages.
