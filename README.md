# Leon — Creative Agency Landing Page

A clean, fully responsive landing page for a creative agency. Built with semantic HTML5 and modern CSS3 — no frameworks, no JavaScript, no dependencies.

**Live Demo → [leon-agency.vercel.app](https://leon-agency.vercel.app)**

---

## Features

- **Responsive layout** — fluid grid that adapts from mobile to wide desktop using CSS Grid and Flexbox
- **BEM architecture** — structured, scalable CSS class naming with zero selector conflicts
- **Accessibility-first** — skip navigation link, ARIA landmarks, meaningful alt text, and full keyboard navigation support
- **Design tokens** — all colors, spacing, typography, and effects defined as CSS custom properties for easy theming
- **Performance-conscious** — lazy-loaded images, explicit width/height on every asset to prevent layout shift, and no render-blocking JavaScript
- **Touch-friendly hover states** — all interactive styles wrapped in `@media (hover: hover)` to prevent sticky-hover on mobile
- **Custom scrollbar** — styled to match the brand color
- **Smooth scroll** — with `prefers-reduced-motion` support for users who prefer less animation

---

## Tech Stack

- HTML5 (semantic landmarks, ARIA)
- CSS3 (custom properties, Grid, Flexbox, `@media` queries)
- Font Awesome 6 (icons)
- Google Fonts — Work Sans

---

## Why This Project

This project demonstrates that a polished, production-quality web presence doesn't require a framework. Every layout challenge is solved with modern CSS alone — from the decorative L-bracket accent in the About section to the responsive three-column services grid that gracefully collapses on smaller screens.

It's a practical reference for:

- Writing CSS that scales without chaos
- Building accessible interfaces without JavaScript
- Structuring HTML that communicates meaning to both browsers and screen readers

---

## Getting Started

No build step. No package manager. Just open the file.

```bash
git clone https://github.com/YOUR_USERNAME/leon-agency.git
cd leon-agency
open index.html
```

Or drop the folder into any static host (Vercel, Netlify, GitHub Pages) and it works instantly.
