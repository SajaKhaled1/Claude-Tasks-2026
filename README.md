# FurniShop — Landing Page

A simple, responsive landing page built with semantic HTML, clean CSS, and a
small amount of vanilla JavaScript, matching the provided design.

## Project structure

```
.
├── index.html          # Markup (semantic sections: header, hero, stats)
├── css/
│   └── style.css       # Styles + responsive rules (design tokens in :root)
├── js/
│   └── script.js       # Mobile navigation toggle
├── assets/
│   └── hero.jpg        # Hero background image
└── README.md
```

## Running

Just open `index.html` in a browser, or serve the folder:

```bash
# Python
python -m http.server 8000
# then visit http://localhost:8000
```

## Notes on assets

`assets/hero.jpg` was extracted from the supplied design screenshot so the page
renders out of the box. For a **pixel-perfect** result, replace it with the
clean, text-free exported sofa photo (same filename) — the page text is drawn in
HTML, so a source image without baked-in text will look best.

## Responsive behaviour

- **Desktop:** horizontal nav, 4-column stats bar.
- **Tablet / mobile (≤768px):** hamburger menu, 2-column stats grid.
- **Small phones (≤420px):** single-column stats.
