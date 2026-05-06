# Surge Build Sprint

Official site for Surge Build Sprint — a 4-day hackathon by Surge where developers build websites using AI tools. The challenge: make the result not look AI-generated.

## Tech Stack

- **Astro** v6 — static site framework
- **Tailwind CSS** v4 — styling via Vite plugin
- **TypeScript** — strict mode
- **Fontsource** — self-hosted variable fonts (Inter Tight + Instrument Sans)

## Getting Started

```bash
npm install
npm run dev
```

Dev server runs at `http://localhost:4321`.

## Build

```bash
npm run build
npm run preview
```

## Project Structure

```
src/
├── components/
│   ├── layout/        # Header, Footer
│   └── marketing/     # Countdown
├── layouts/           # BaseLayout
├── pages/             # All routes
│   ├── index.astro
│   ├── rules.astro
│   ├── stack.astro
│   ├── getting-started.astro
│   ├── leaderboard.astro
│   └── faq.astro
└── styles/
    └── global.css     # Design tokens, theme system
```

## Features

- Dark/light theme with system detection and manual toggle (persisted)
- Page transitions via Astro ClientRouter
- Responsive across all breakpoints
- Leaderboard with skeleton loading state
- FAQ accordion with animated expand/collapse

## Environment

No environment variables required for the static site. All content is currently hardcoded.

## Deployment

Designed for Railway. Push to deploy.
