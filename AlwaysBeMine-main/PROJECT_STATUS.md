# AlwaysBeMine - Project Status

## What was fixed
- **`html/index.html`**: Fixed broken paths for favicons and script source
  - Icon paths changed from `/AlwaysBeMine-main/public/...` to `../public/...`
  - Script src changed from `/AlwaysBeMine-main/gifData/main.jsx` to `../src/main.jsx`

## Project structure (active files)
- Root `index.html` — main HTML entry (used by Vite)
- `src/main.jsx` — React entry point
- `src/App.jsx` — main proposal logic (Yes/No buttons, music, GIFs, popups)
- `src/MouseStealer.jsx` — "No" button escape effect
- `src/MarqueeProposal.jsx` — scrolling text component
- `src/Preloaders/` — heart canvas preloaders
- `src/assets/` — images, GIFs, audio files
- `public/` — static favicons/icons
- `vite.config.js`, `tailwind.config.js`, `postcss.config.js`, `package.json` — config files

## Backup folders (not used by main build)
- `html/`, `js/`, `json/`, `gifData/` at root — old/duplicate copies

## How to run later
1. Install Node.js from https://nodejs.org/
2. Open terminal in this folder
3. Run: `npm install`
4. Run: `npm run dev`
5. Open browser to `http://localhost:5173`

## To deploy online (24/7)
- Push to GitHub, then connect to Vercel (free)
- Build command: `npm run build`
- Output directory: `dist`
