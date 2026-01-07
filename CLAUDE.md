# NS4 Companion Support Website

## Development Instructions

**IMPORTANT:** Always use the `frontend-design` skill when making UI changes.
This ensures professional, high-quality design consistent with the Nord-inspired theme.

## Tech Stack
- Astro 4.x
- Tailwind CSS v4
- Markdown for guide content

## Design System

### Colors (Nord-inspired)
- Background: `#1a1a1a` (dark gray)
- Surfaces: `#2a2a2a` (cards/sections)
- Primary: `#c8102e` (Nord red)
- Text: `#ffffff` (white)
- Muted: `#999999` (gray)
- Hover: `#e01b3c` (lighter red)

### Typography
- Font: Inter or system fonts
- Monospace for code/MIDI references

### Responsive
- Mobile-first approach
- Breakpoints: sm (640px), md (768px), lg (1024px)

## Commands
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## Project Structure
```
src/
├── layouts/Layout.astro    # Base layout
├── components/             # Reusable components
├── pages/                  # Route pages
├── content/guide/          # Markdown guide content
└── styles/global.css       # Tailwind styles
```

## Content Sources

**IMPORTANT:** Before making documentation changes, always check if the app's docs have been updated:

```
/Users/kongsjordenstudio/Documents/App_utvikling/Nord_Stage_4/NS4Companion/docs/
```

Key files to sync with:
- `USER_GUIDE.md` → `guide.astro`
- `FEATURES.md` → `features.astro`

Website pages should reflect the latest app documentation. If user mentions doc updates or you're working on guide/features pages, compare with the app's .md files first.
