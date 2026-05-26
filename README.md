# Burnt Crumbs

Homepage for Burnt Crumbs (Irvine, CA), built with Astro + Tailwind v4.

## Develop

```
npm install
npm run dev
```

## Build

```
npm run build
```

Static output is emitted to `dist/`.

## Deploy to Cloudflare Pages

- **Framework preset**: Astro
- **Build command**: `npm run build`
- **Output directory**: `dist`

## Structure

```
src/pages/index.astro      — the homepage
src/layouts/BurntLayout.astro — document shell + interactions (carousel, stop-motion, sticky CTA)
src/styles/burnt.css       — palette, fonts, and animations
public/media/              — all images (hero shots, product photos, slideshow frames)
```
