# Allen Irrigation Company Website

Static marketing website for Allen Irrigation Company (Mooresville, IN) built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com).

## Pages

- **Home** — Hero, services overview, about preview, stats, testimonials, CTA
- **About** — Company history, owner bio, stats
- **Services** — Overview + individual pages for Irrigation, Landscape Lighting, Holiday Lighting
- **Testimonials** — Client reviews
- **FAQ** — Accordion-style frequently asked questions
- **Contact** — Contact form, hours, map placeholder

## Development

```bash
# Install dependencies
npm install

# Start dev server (http://localhost:4321)
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

The `npm run build` command generates static files in `dist/`. Deploy to any static host:

- **Netlify** — Connect repo, build command: `npm run build`, publish dir: `dist`
- **Vercel** — Connect repo, framework preset: Astro
- **GitHub Pages** — Use `@astrojs/github-pages` adapter or deploy `dist/` manually
- **Cloudflare Pages** — Connect repo, build command: `npm run build`, output dir: `dist`

## Tech Stack

- Astro 5
- Tailwind CSS 3
- Google Fonts (Montserrat + Open Sans)
- Placeholder images from Unsplash

## Customization

- Colors: `tailwind.config.mjs` → `theme.extend.colors`
- Content: Edit `.astro` files in `src/pages/`
- Components: `src/components/`
- Layout: `src/layouts/BaseLayout.astro`
