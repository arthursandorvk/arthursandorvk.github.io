# Academic Portfolio — Arthur Sandor Voundi Koe

Personal academic portfolio website — publications, code, and contact. Applied cryptography: ABE, mobile cloud security; blockchain security and privacy. Xidian University. https://arthursandorvk.github.io/ Plain HTML/CSS/JS in a single
`index.html` — no build step, no dependencies.

## Deploy on GitHub Pages

1. Create a new public repository (e.g. `portfolio` or
   `arthursandorvk.github.io`).
2. Copy `index.html` to the repository root and push:

   ```bash
   git init && git add . && git commit -m "Initial portfolio"
   git remote add origin https://github.com/arthursandorvk/<repo>.git
   git push -u origin main
   ```

3. In the repository: **Settings → Pages → Build and deployment →
   Deploy from a branch**, select `main` / `(root)`, and save.
4. The site goes live within a minute at
   `https://arthursandorvk.github.io/<repo>/`
   (or `https://arthursandorvk.github.io/` if the repo is named
   `arthursandorvk.github.io`).

## Editing

All content lives in `index.html`:

- **Publications** — each entry is a `<div class="pub">` block inside a
  year section (`<div class="pub-year">`); update the `.year-count` label
  when adding or removing papers.
- **Affiliation / contact** — hero section and the Contact section.
- Fonts (Source Serif 4, Inter, JetBrains Mono) load from Google Fonts;
  the site works offline with system fallbacks.

