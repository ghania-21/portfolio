# Ghania Fatima — Portfolio

A premium, dark, editorial-style developer portfolio built with plain HTML, CSS and JavaScript (no build step, no framework).

## Run it
Just open `index.html` in a browser, or serve the folder locally:

```
python3 -m http.server 8080
```

then visit `http://localhost:8080`.

To publish it, drag-and-drop this whole folder into **Netlify Drop**, or push it to a **GitHub repo** and enable **GitHub Pages**.

## Folder structure
```
/assets/images   → your photo (ghania-profile.jpg / .png)
/css/style.css   → all styling, design tokens at the top
/js/main.js      → navbar, mobile menu, scroll reveal, cursor, parallax, magnetic buttons
index.html       → page content
```

## Things to personalize before you publish

1. **Real links** — search `index.html` for `https://github.com/` and `https://linkedin.com/` and `mailto:hello@example.com`, and swap in your real profile URLs and email.
2. **Project links** — each project's "Live Demo" and "GitHub" buttons currently use `#` placeholders (search for `href="#"` inside the `.project` blocks) — point these at your real deployed projects and repos.
3. **Project screenshots** — your real screenshots for all 4 projects (Netflix Clone, Mission Control Dashboard, AI Interview Platform, Wander) are already in place under `/assets/images/`, shown inside a clean browser-window frame. If you update a project later, just replace the matching file (same filename) with your new screenshot, or swap the `src` in `index.html`.
4. **Photo** — your uploaded photo is already wired into the hero and About section (`assets/images/ghania-profile.jpg`). Swap the file if you want to use a different one, keeping the same filename, or update the `src` in `index.html`.

## Notes
- Fonts (Manrope + Inter) load from Google Fonts, so an internet connection is needed for the exact typography — it falls back gracefully to a system sans-serif offline.
- Respects `prefers-reduced-motion`, disables the custom cursor and parallax on touch devices, and is tested down to a 320px viewport.
