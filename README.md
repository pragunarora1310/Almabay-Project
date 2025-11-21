# OctoHub — GitHub-like Red-Dark Theme (Static Demo)

A single-page, static recreation inspired by **github.com**, redesigned in a vivid **red–dark** theme with accessible styles, subtle UI animations, and fully responsive layouts. Includes demo **Sign up** and **Sign in** pages with simple client-side validation.

This repo is intended as a frontend UI mock for learning, prototyping, or theming experiments. It does **not** include any backend or real authentication.

---

## What you get

- `index.html` — main landing page (hero, features, customers, testimonial, footer).
- `signup.html` — sign-up form (client-side validation + demo redirect).
- `login.html` — sign-in form (client-side validation + demo redirect).
- `styles.css` — single shared stylesheet (layout, colors, animations, responsive rules).
- All files are static and interlinked; open `index.html` to start.

---

## Features

- **Red-dark theme** with stronger accent colors (`--accent`, `--accent-2`, `--accent-3`).
- **Fully responsive** design: desktop → tablet → mobile (hamburger menu + mobile nav).
- **Subtle UI animations**: entrance reveals, hover lifts, CTA pulse, and reveal-on-scroll using IntersectionObserver.
- **Accessibility-minded**:
  - Focus outlines on inputs and controls.
  - `prefers-reduced-motion` support (animations disabled when requested).
  - Semantic HTML and ARIA attributes for the header and mobile nav.
- **Demo auth flows**: basic client-side validation with friendly alerts (no server).
- Clean, modern layout with glassy cards and soft shadows.

---

## Quick start

1. **Download** or copy the files into a single folder.
2. Open `index.html` in your browser.

Optional: run a small static server (useful for testing mobile emulation or service workers).

