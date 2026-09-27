# BMI Calculator — Pure HTML & CSS Tool

A practical, everyday health calculator built **without JavaScript** using semantic HTML and modern CSS. Features metric/imperial unit switching, responsive design, and color-coded BMI categories.

![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-blue)

## ✨ Features
- **Zero JavaScript** — everything works via HTML form + CSS `:checked` logic
- **Metric / Imperial toggle** — radio buttons switch units and fields instantly
- **CSS-only calculation** — uses custom properties to display results
- **Responsive** — works on mobile and desktop
- **Accessible** — proper labels, ARIA roles, semantic markup

## 🛠️ How It Works (Technical)
- `<input type="radio">` for unit selection
- CSS `:checked` to show/hide field groups
- Custom properties (`--bmi-value`, `--bmi-category`) for the result
- Color coding based on BMI ranges (blue → green → yellow → red)

## 🚀 Run locally
```bash
open index.html
```

Or serve with Python:
```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

## 📦 Git & GitHub workflow
```bash
# Add remote (replace with your repo URL)
git remote add origin https://github.com/YOUR_USERNAME/html-css-task.git

# Push (you may be prompted for a Personal Access Token)
git push -u origin main

# Enable GitHub Pages:
# https://github.com/YOUR_USERNAME/html-css-task/settings/pages
```

## 🖥️ Demo Screenshot

![BMI Calculator Screenshot](https://i.imgur.com/placeholder.png)

## 📚 Built with
- HTML5 (semantic, forms, accessibility)
- CSS3 (variables, Flexbox, Grid, custom properties)
- Git & GitHub

---

© 2026 — Built with pure HTML & CSS for real-world use.
