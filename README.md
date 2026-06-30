# Dillon Drobena — Personal Website

A single-page personal/portfolio site. Plain HTML, CSS, and a little vanilla JS — **no build step, no dependencies.**

## Structure
```
personal-website/
├── index.html        # all content/markup
├── styles.css        # styling (dark theme, responsive)
├── script.js         # mobile nav, scroll state, footer year
└── assets/
    ├── avatar.jpg                  # GitHub profile photo
    └── Dillon_Drobena_Resume.pdf   # linked from the "Résumé" buttons
```

## Run locally
Just open `index.html` in a browser. Or serve it (better for testing relative paths):

```bash
# from this folder
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (pick one — all free)
- **GitHub Pages:** push these files to your `dillondrobena.github.io` repo (or any repo + enable Pages). It's static, so it works as-is.
- **Vercel / Netlify:** drag-and-drop the folder, or connect the repo. No framework preset needed — it's a static site.

## Editing
- Text/content lives in `index.html` (sections are clearly commented: HERO, ABOUT, SKILLS, EXPERIENCE, PROJECTS, EDUCATION, CONTACT).
- Colors are CSS variables at the top of `styles.css` (`--accent`, `--bg`, etc.).
- To update the photo, replace `assets/avatar.jpg`. To update the résumé, replace `assets/Dillon_Drobena_Resume.pdf`.

## Notes
- The projects shown are described generically (no client names), matching your résumé.
- Add a custom domain later via your host's settings if you want (e.g., `dillondrobena.com`).
