# juliosantos73.github.io

Personal website and online résumé of **Julio Santos**, published via GitHub Pages.

🔗 https://juliosantos73.github.io/

---

## Stack

Pure HTML + CSS + JavaScript. No frameworks, no bundler, no runtime dependencies.

## Structure

```
index.html              — single page with all content and logic
assets/
  css/common.css        — all styles
  img/
    julio-linkedin.jpeg — profile photo (hero)
    favicon.svg         — favicon with initials JS
robots.txt              — crawler permissions
sitemap.xml             — sitemap for search engines
.gitignore
```

## Features

- **Language switcher** 🇵🇹 🇺🇸 🇪🇸 — translations via `data-i18n` and `T` object, saved in `localStorage`
- **Dark / light mode** — toggle with `data-theme` on `<html>`, no flash on load
- **Responsive nav** — hamburger menu on mobile, sticky with blur
- **GitHub Projects** — section that automatically fetches repos with the `featured` topic via public API, grouped by secondary topic
- **Entry animations** — Intersection Observer with fade + slide up, respects `prefers-reduced-motion`
- **SEO** — JSON-LD Schema.org Person, meta keywords, canonical URL, sitemap, Google Search Console verified
- **Open Graph / Twitter Card** — meta tags for social sharing
- **SVG Favicon** — initials JS in accent colour, consistent with nav logo

## Sections

1. Hero — photo, name, title, tagline, CTAs
2. About — background, experience framing, education
3. Experience — timeline with 4 positions
4. Stack — 5 technology categories
5. Projects — GitHub repos with the `featured` topic
6. Education & Certifications — degree + Samsung Ocean + UniFavip Wyden
7. Footer — contact and social links

## Deploy

```bash
git add .
git commit -m "description"
git push origin main
```

GitHub Pages publishes automatically within ~1 minute after push.
Status: https://github.com/juliosantos73/juliosantos73.github.io/actions

## Highlighting GitHub Projects

For a repository to appear in the projects section, add the `featured` topic in its Settings → About ⚙️ → Topics.

To group projects by category, add a second topic (e.g. `backend`, `frontend`, `devops`). The section will render a subgroup header automatically.
