# insuranceagencysites.com

The published site. **This repository is a deploy target, not the source.**

The source lives in the private venture repo at `brand/` and is built with Astro.
To publish a change, edit it there and run `node scripts/publish-brand.mjs`,
which rebuilds and force-pushes here. Editing files in this repository directly
will be overwritten on the next publish.
