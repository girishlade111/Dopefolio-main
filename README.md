# Dopefolio

Dopefolio is a blazing-fast, multipage portfolio website template for developers and designers — clean, responsive, and SEO-friendly, built with plain HTML, SCSS, and vanilla JavaScript.

## Features

- **Multipage layout** — home page plus dedicated project case-study pages (`project-1.html`, `project-2.html`, `project-3.html`)
- **Responsive design** — looks great on mobile, tablet, and desktop
- **SEO-friendly** — semantic HTML with meta tags ready for search indexing
- **SCSS workflow** — styles authored in `sass/`, compiled to `css/style.css` with PostCSS autoprefixing and minification
- **No framework bloat** — zero client-side dependencies, instant load times
- **Project showcase** — portfolio sections for about, skills, projects, and contact

## Tech Stack

- HTML5, CSS3 (compiled from SCSS)
- Sass / Node-Sass, PostCSS + Autoprefixer
- Vanilla JavaScript (`index.js`)

## Quick Start

Open the template directly — no build step required for viewing:

```bash
cd Dopefolio-main
# then open index.html in your browser
```

To rebuild the CSS after editing SCSS:

```bash
cd Dopefolio-main
npm install
npm run build   # autoprefix + compress css/style.css
```

## Project Structure

```
Dopefolio-main/
├── index.html          # Home page
├── project-1.html      # Project case-study pages
├── project-2.html
├── project-3.html
├── index.js            # Site interactivity
├── css/style.css       # Compiled styles
├── sass/               # SCSS sources
└── assets/             # Images (jpeg, png, svg)
```

## Customization

- Edit `index.html` and the `project-N.html` pages to add your name, bio, projects, and contact details.
- Update styles in `sass/` and rebuild with `npm run build`.
- Replace images under `assets/` with your own screenshots and photos.

## Deployment

This is a static site — deploy the `Dopefolio-main/` directory to any static host (GitHub Pages, Cloudflare Pages, Netlify, Vercel). No server or build service required.

## License

GPL-3.0 — see `LICENSE`.

---

**Built by Girish Lade** — [ladestack.in](https://ladestack.in)
