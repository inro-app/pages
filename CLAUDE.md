# Context for Claude Code

This repo hosts standalone static HTML pages (slide decks, presentations, etc.) published via GitHub Pages at `https://inro-app.github.io/pages/`.

## Rules for adding pages

- Drop HTML files in the **repo root** — no subdirectories
- File names: lowercase, hyphens only, `.html` extension (e.g. `q3-investor-deck.html`)
- Each file must be a **fully self-contained** HTML page — all CSS and JS inlined or embedded, no external build step, no frameworks required
- After creating a file, update the table in `README.md` with the filename and a short description

## What not to do

- Do not create subdirectories for pages
- Do not add a build system, package.json, or any dependencies
- Do not modify `index.html` (it redirects to www.inro.social)
