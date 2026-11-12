# Apogee site

Static Astro landing page with self-hosted fonts. No server runtime or adapter required.

## Local development

Requires Node.js 22.12 or later.

```sh
npm ci
npm run dev
```

`npm run check` validates Astro and TypeScript. `npm run build` outputs `dist/`; `npm run preview` serves the build.

## Deploying

Hosted on Vercel with the Astro preset (build `npm run build`, output `dist`). Pushes to `main` deploy to production; pull requests get preview deployments.

## Editing

- `src/pages/index.astro`: the whole page, including its styles.
- `public/screenshots/apogee-macos.png`: real macOS capture, connected to a CARTA Sport.
- `public/apogee.png`: app artwork.

Earlier design options live on the local `test` branch.
