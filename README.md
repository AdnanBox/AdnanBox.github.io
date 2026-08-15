# AdnanBox.github.io

Personal portfolio site, built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com).

## Development

```sh
npm install
npm run dev       # local dev server with hot reload
npm run build     # production build to dist/
npm run preview   # preview the production build locally
```

## Structure

- `src/data/` — site content (bio, experience, education, projects, courses)
- `src/components/`, `src/layouts/` — shared layout, nav, footer, and card UI
- `src/pages/` — one file per route
- `public/` — static assets (images, certificates)

Deployed via Netlify (`netlify.toml`) on pushes to `master`.
