# NS4 Companion Support Website

Support website for NS4 Companion - the companion app for Nord Stage 4 keyboard owners.

**Live site:** https://ns4.kongsjorden-studio.no

## Tech Stack

- [Astro](https://astro.build) - Static site generator
- [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS
- Custom Nord-inspired dark theme

## Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
src/
├── layouts/Layout.astro     # Base layout
├── components/              # Reusable components
│   ├── Header.astro
│   ├── Footer.astro
│   ├── Hero.astro
│   ├── FeatureCard.astro
│   ├── FaqAccordion.astro
│   └── Placeholder.astro
├── pages/                   # Route pages
│   ├── index.astro          # Home
│   ├── features.astro       # Features
│   ├── guide.astro          # User Guide
│   ├── faq.astro            # FAQ
│   ├── support.astro        # Support
│   └── privacy.astro        # Privacy Policy
└── styles/global.css        # Tailwind + custom styles
```

## Deployment

Build the site and deploy the `dist/` folder to your web server:

```bash
npm run build
```

The `dist/` folder contains static files ready for any web server.

## Contributing

Report bugs and request features via [GitHub Issues](https://github.com/kongsjorden/NS4-Support/issues).

## License

All rights reserved.
