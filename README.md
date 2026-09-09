# Asylum Studios — Pricing Page Mockup

A single self-contained `index.html` — no build step, no dependencies.

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `asylum-studios-site`).
2. Upload `index.html` from this folder to the repo root (drag-and-drop on github.com works, or `git add`/`commit`/`push`).
3. In the repo: **Settings → Pages**.
4. Under "Build and deployment", set **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)** → **Save**.
5. Wait ~1 minute, then your site is live at `https://<your-username>.github.io/<repo-name>/`.

## Notes
- The room-gallery and hero photos load from external URLs (the studio's existing site) — an internet connection is required to see them; everything else (fonts, logo, layout, interactions) is bundled in the file.
- To update content later, edit `index.html` directly and re-push.
