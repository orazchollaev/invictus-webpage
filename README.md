# Invictus Landing Pages

Landing pages for the Invictus apps. Built with Astro.

- `/` — Invictus Tournament Maker
- `/national-manager/` — Invictus National Manager

## Development

```bash
pnpm install
pnpm dev
```

## Build

```bash
pnpm build
pnpm preview
```

## Deploy

Hosted on Firebase Hosting.

```bash
pnpm build
firebase deploy
```

## Structure

- `src/pages/index.astro` — Tournament Maker page
- `src/pages/national-manager.astro` — National Manager page
- `src/components/` — shared nav between the apps and the "More from Invictus" block
- `src/layouts/Layout.astro` — shared layout (title, description, favicon, fonts)
- `src/styles/landing.css` — styles shared by both pages
- `public/` — static assets (favicon, icons, screenshot, robots.txt, sitemap.xml)
- `public/national-manager/` — National Manager logo, favicon and screenshots
