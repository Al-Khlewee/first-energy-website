# First Energy — Bilingual Website

A single-file, Apple-style minimalist website for **First Energy**, available in **English & Arabic** (with full RTL support).

## Sections
1. **Oil Services** — deep navy / blue
2. **General Contracting** — amber / orange
3. **General Trading** — emerald / green
4. **Real Estate Development & Investments** — indigo / violet
5. **Public Transport** — rose / pink

Each section has its own color theme, image, and activity chips.

## Features
- 🌐 One-click **EN ⇄ AR** language switch (remembers your choice, auto-detects Arabic browsers)
- 📱 Fully responsive
- ✨ Scroll-reveal animations, frosted-glass nav (Apple-style)
- 📄 100% self-contained in `index.html` — no build step, no dependencies

## Deploy on GitHub Pages
1. Go to **Settings → Pages** in the repository.
2. Under **Build and deployment → Source**, choose **GitHub Actions**.
3. Pushes to `main` will deploy automatically through `.github/workflows/pages.yml`.
4. Once Pages is enabled, the live site will be available at `https://al-khlewee.github.io/first-energy-website/`.

## Customize
- **Images:** replace the Unsplash URLs in each `<section>` with your own photos (e.g. `images/oil.jpg`).
- **Colors:** edit the `--c-*` variables in the `:root` block at the top of `index.html`.
- **Contact:** update the email/phone in the `#contact` section and the footer.
