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
1. Create a new repository and upload `index.html` (and this `README.md`).
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then **Save**.
5. Your site will be live at `https://github.com/Al-Khlewee/first-energy-website` and the Pages URL will be `https://al-khlewee.github.io/first-energy-website/` once Pages is enabled.

### Quick command-line version
```bash
git init
git add index.html README.md
git commit -m "First Energy bilingual website"
git branch -M main
git remote add origin https://github.com/Al-Khlewee/first-energy-website.git
git push -u origin main
```

## Customize
- **Images:** replace the Unsplash URLs in each `<section>` with your own photos (e.g. `images/oil.jpg`).
- **Colors:** edit the `--c-*` variables in the `:root` block at the top of `index.html`.
- **Contact:** update the email/phone in the `#contact` section and the footer.
