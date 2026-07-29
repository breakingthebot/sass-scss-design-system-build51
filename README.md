# Build 51: Sass/SCSS Design System — Breaking The Bot Multiverse

[![Vercel Deployment](https://img.shields.io/badge/Vercel-Live%20Demo-000000?style=for-the-badge&logo=vercel)](https://sass-scss-design-system-build51.vercel.app)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/breakingthebot/sass-scss-design-system-build51)
[![Sass](https://img.shields.io/badge/Sass-SCSS%20Modules-CC6699?style=for-the-badge&logo=sass)](file:///C:/Users/marve/Desktop/AI-286-Builds/Build_51/scss/main.scss)
[![JavaScript](https://img.shields.io/badge/JavaScript-0%25%20No%20JS-F7DF1E?style=for-the-badge)](file:///C:/Users/marve/Desktop/AI-286-Builds/Build_51/index.html)

---

## 🌟 Overview

**Build 51** showcases a professional-grade **Sass/SCSS Design System** featuring variables, mixins, functions, maps, control loops, and nested components compiled into clean, high-performance CSS. Applied to the **Breaking The Bot TikTok Character Worldbuilding Multiverse** landing page with 100% Pure CSS and **Zero JavaScript**.

### 🌐 Live Production Demo
- **Live Vercel Application**: [https://sass-scss-design-system-build51.vercel.app](https://sass-scss-design-system-build51.vercel.app)
- **GitHub Codebase**: [https://github.com/breakingthebot/sass-scss-design-system-build51](https://github.com/breakingthebot/sass-scss-design-system-build51)

---

## 📂 Modular SCSS Architecture

```
Build_51/
├── scss/
│   ├── abstracts/
│   │   ├── _variables.scss      # Design tokens (colors, fonts, breakpoints)
│   │   ├── _mixins.scss         # Flex, grid, glassmorphism, respond-to mixins
│   │   └── _functions.scss      # rem() calculation functions
│   ├── base/
│   │   ├── _reset.scss          # CSS reset & state hacks
│   │   └── _typography.scss     # Google Fonts & typography styles
│   ├── components/
│   │   ├── _navbar.scss         # Sticky navbar & mobile toggle
│   │   ├── _buttons.scss        # Button variants
│   │   ├── _hero.scss           # Hero section & animations
│   │   ├── _cards.scss          # Feature & bio card blocks
│   │   ├── _polaroid.scss       # 3D Polaroid flip card table
│   │   ├── _radio.scss          # Sound wave spectrum visualizer
│   │   └── _modals.scss         # Zero-JS :target dossier modals
│   └── main.scss                # Primary entrypoint compiling to css/style.css
├── css/
│   └── style.css                # Clean compiled CSS
├── index.html                   # HTML5 landing page
└── package.json                 # Sass compilation scripts
```

---

## 🔥 Key Highlights

- **⚙️ SCSS Maps & Media Query Mixin**: Responsive breakpoint handling via `@mixin respond-to($breakpoint)` utilizing `map.has-key` and `map.get`.
- **🔄 SCSS Control Loops**: Staggered animation delays for the 12 equalizer bars generated with `@for $i from 1 through 12`.
- **⚡ 0kb JS Executable Overhead**: 100% Pure CSS interactivity — zero script tags, zero framework runtimes.
