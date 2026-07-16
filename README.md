# antiswarm.github.io
repo for v0.1 landing page, hosted thru github pages

Built with [Astro](https://astro.build) (requires Node >=22.12.0). See [design-prompt.md](design-prompt.md) for design spec.

```sh
npm install
npm run dev      # local dev server
npm run build    # static build to dist/
```

Deploys automatically to GitHub Pages via `.github/workflows/deploy.yml` on push to `main`. Enable GitHub Pages with source "GitHub Actions" in repo Settings → Pages.
