# BMI Calculator — Polished Web App

A production-quality Body Mass Index calculator with dark mode, animated UI, real-time validation, and smooth animations. Built with plain HTML, CSS, and minimal JavaScript — no frameworks.

![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-blue)

## ✨ Features
- **Dark mode** — automatic via `prefers-color-scheme`, manual via `[data-theme]`
- **Animated unit toggle** — sliding thumb with cubic-bezier easing
- **Real-time validation** — inline errors, disabled Calculate button until valid
- **Result animation** — fade + slide-up entrance with reflow trigger
- **Legend highlight** — `color-mix()` background + inset shadow on active category
- **Healthy weight range** — shows in kg **or** lb matching current unit
- **Full accessibility** — `aria-live`, proper labels, `focus-visible`, `role=alert`
- **Reduced motion** — respects `prefers-reduced-motion`
- **Safe area insets** — handles notched devices
- **System font stack** — Manrope (display) + Inter (UI)

## 🛠️ Tech Stack
- **HTML5** — semantic, accessible, no external deps
- **CSS3** — custom properties, `color-mix()`, transitions, dark mode
- **JavaScript** — single IIFE module, no frameworks
- **PWA-ready** — `site.webmanifest` + icons for "Add to Home Screen"

## 🚀 Run locally
```bash
cd ~/MyProjects/html-css-task
python3 -m http.server 8000
# Visit http://localhost:8000
```

## 📱 Install as PWA (Chrome / Edge / Safari)
1. Open the deployed URL
2. Tap Share → **Add to Home Screen**
3. Opens as standalone app

## 📦 Git & GitHub
```bash
git push -u origin main
```
Then enable GitHub Pages: Settings → Pages → Deploy from branch → `main` / `root`

## 📚 Learning Outcomes (Day 1-3)
- Day 1: Semantic HTML, forms, labels, accessibility attributes
- Day 2: CSS variables, dark mode, transitions, `color-mix()`, layout
- Day 3: Full app + Git + GitHub Pages deployment

---

© 2026 — Built with HTML, CSS, & minimal JS.