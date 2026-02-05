# Photography Portfolio

**Short description**
A clean, responsive single-page photography portfolio built with plain HTML and CSS to showcase galleries and contact information.

---

## Quick start
- Open locally: double-click `index.html` or run a local server:
- Recommended: use VS Code Live Server extension for hot reload.

---

## Project structure
- `index.html` — main page and gallery markup
- `style.css` — styles and layout
- `images/` — (create) put full-size and thumbnail images here
- `Readme.md` — this file

---

## Features
- Responsive gallery grid
- Lightbox-ready image links (optional JS plugin)
- Lazy-loaded images (`loading="lazy"`) for performance
- Semantic HTML for accessibility

---

## Add images (recommended structure)
Organize your images like:
```
images/
  thumbs/
  full/
```
Example markup for a gallery item:

```html
<figure class="photo-card">
  <a href="images/full/photo1-large.jpg" data-lightbox="gallery">
    <img src="images/thumbs/photo1.jpg" alt="Descriptive alt text" loading="lazy">
  </a>
  <figcaption>Photo title — Location / Year</figcaption>
</figure>
```

- Use descriptive `alt` text for accessibility and SEO.
- Optimize images (WebP or compressed JPEG) for faster loading.

---

## Customize
- Colors & spacing: edit `style.css` (consider CSS variables at the top)
- Add categories/tags by grouping photos into sections or adding `data-` attributes
- Add a lightbox library (e.g., Lightbox2 or GLightbox) if you want modal viewing

---

## Accessibility 
- Use semantic tags: `<main>`, `<header>`, `<footer>`, `<figure>`, `<figcaption>`
- Provide meaningful `alt` attributes
- Add meta description and Open Graph tags in the `<head>`

---

## Deployment (GitHub Pages)
1. Push your repo to GitHub
2. Settings → Pages → choose `main` branch → root
3. Visit live site https://waunaneville-design.github.io/MY-PHOTOGRAPH-PORTFOLIO/

---

##  License
This project is open-source. Add a license (MIT recommended) to `LICENSE` if needed.

---

## Contact
- Photographer Name — waunaneville@gmail.com
- Portfolio / Instagram — https://www.instagram.com/i.n3vill3/?__pwa=1#
