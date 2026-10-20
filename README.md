# Sara Kim's personal site

This repository publishes [saykig.github.io](https://saykig.github.io/) through GitHub Pages. Pages serves the generated site from `docs/` on `main`. The Next.js source is maintained separately in `saykig/sarakim23.vercel.app`; `docs/` is its static export, so the generated files should be updated together rather than edited individually.

The site in `docs/sara-poet/` redirects the former poetry address to [Selected Poems](https://sarakim23.vercel.app/). Keep `docs/.nojekyll` so GitHub Pages serves Next.js's `_next/` assets.

To publish a source update, build the source project, sync its `out/` directory into this repository's `docs/`, keep `.nojekyll`, then commit and push `main`. The source project's README has the build command.
