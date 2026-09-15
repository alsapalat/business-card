# Multisys cards

Single-page business card app for GitHub Pages. No build step.

## Deploy
1. Push this folder to a repo (e.g. `multisys-cards`).
2. Settings → Pages → Source: **Deploy from a branch** → `main` / `/ (root)`.
3. Open `https://<user>.github.io/multisys-cards/`.

## Routes
- `#/` — your saved cards (localStorage)
- `#/new`, `#/edit/:id` — create / edit
- `#/view/:id` — card with QR + share link
- `#/card?d=…` — public page the QR opens (Save contact / Save image)

## Customise
Edit the `COMPANY` object at the top of the script in `index.html` (name, logo). Brand colours are CSS variables in `:root`.
