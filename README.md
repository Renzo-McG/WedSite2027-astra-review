# Astra wedding review

Independent Travel & Stay review build only.

Review: https://renzo-mcg.github.io/WedSite2027-astra-review/travel/

Source branch: `feat/travel-island-guide`

Source commit: `d901db529eece86d28b53b8609ef526da205e20c`

This repository contains the compiled interactive site and its public assets. It has no deployment connection to the production repository or the Claude review repository. All HTML pages are marked `noindex, nofollow`.

Build command from the source checkout:

```sh
pnpm exec astro build --base /WedSite2027-astra-review --outDir ../WedSite2027-astra-review-publish
```

GitHub Pages serves the `main` branch root. `.nojekyll` preserves Astro assets.
