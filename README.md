# 📸 Photography Portfolio

**Short description**
A clean, responsive single-page photography portfolio built with plain HTML and CSS to showcase galleries and contact information.

---

## 🚀 Quick start
- Open locally: double-click `index.html` or run a local server:
  - `python -m http.server 8000` → visit `http://localhost:8000`
- Recommended: use VS Code Live Server extension for hot reload.

---

## 📁 Project structure
- `index.html` — main page and gallery markup
- `style.css` — styles and layout
- `images/` — (create) put full-size and thumbnail images here
- `Readme.md` — this file

---

## ✨ Features
- Responsive gallery grid
- Lightbox-ready image links (optional JS plugin)
- Lazy-loaded images (`loading="lazy"`) for performance
- Semantic HTML for accessibility

---

## 🖼️ Add images (recommended structure)
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

## ⚙️ Customize
- Colors & spacing: edit `style.css` (consider CSS variables at the top)
- Add categories/tags by grouping photos into sections or adding `data-` attributes
- Add a lightbox library (e.g., Lightbox2 or GLightbox) if you want modal viewing

---

## ♿ Accessibility & SEO tips
- Use semantic tags: `<main>`, `<header>`, `<footer>`, `<figure>`, `<figcaption>`
- Provide meaningful `alt` attributes
- Add meta description and Open Graph tags in the `<head>`

---

## 🚀 Deployment (GitHub Pages)
1. Push your repo to GitHub
2. Settings → Pages → choose `main` branch → root
3. Visit `https://<username>.github.io/<repo-name>/`

---

## 🤝 Contributing
- Fork, create a feature branch, and send a PR
- Keep commits small and descriptive; include screenshots for UI changes

---

## 📄 License
This project is open-source. Add a license (MIT recommended) to `LICENSE` if needed.

---

## ✉️ Contact
- Photographer Name — email@example.com
- Portfolio / Instagram — add your links

> ⚠️ Replace placeholder text and images with your real content before publishing.
