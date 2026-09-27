# Crop Studio — Landing Page

A dark, modern marketing landing page for **Crop Studio**, a screen-privacy tool that lets you crop out sensitive information on your screen during work calls — "Protect Your Privacy, Share What Matters."

> **Built by Girish Lade** — more free tools at [ladestack.in](https://ladestack.in)

## Features

- **Hero section** — bold headline with interactive grid background, ShineBorder CTA card, and demo video button
- **Features section** — product capability highlights with icons and copy
- **Showcase section** — visual product screenshots/previews
- **Integrations section** — "seamlessly integrates with your..." stack logos/badges
- **Partners section** — social proof / partner logos
- **Announcement bar + Navbar** — sticky navigation with theme provider
- **Dark-first design** — black background, white/10 borders, glow accents
- **Responsive** — mobile-first Tailwind layouts

## Tech Stack

- **Next.js 15** (App Router, static export) + **React 19** + **TypeScript**
- **Tailwind CSS** + **shadcn/ui** (Radix UI primitives)
- **next-themes** for dark mode
- **lucide-react** icons

## Quick Start

```bash
# install dependencies
npm install

# run the dev server
npm run dev
# open http://localhost:3000

# production build (static export to ./out)
npm run build

# serve the static build
npx serve out
```

## Project Structure

```
app/                  # Next.js App Router (layout, page, globals.css)
components/
  header.tsx / navbar.tsx      # Navigation
  announcement-bar.tsx
  hero-section.tsx             # Interactive grid + ShineBorder hero
  features-section.tsx
  showcase-section.tsx
  integration-section.tsx
  partners-section.tsx
  ui/                 # shadcn/ui primitives
  theme-provider.tsx
lib/utils.ts          # className helpers
public/               # Static assets / screenshots
styles/
```

## Environment Variables

None — pure static landing page, no secrets or API keys.

## Deployment

Static site. Build with `npm run build` (configured with `output: 'export'`, images unoptimized) and deploy the `out/` directory to any static host — GitHub Pages, Cloudflare Pages, Netlify, or Vercel.

## License

Free to use and modify.
