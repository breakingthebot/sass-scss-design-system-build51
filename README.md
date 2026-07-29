# Build 51: ApexUI — Enterprise Sass/SCSS Design System

[![Vercel Deployment](https://img.shields.io/badge/Vercel-Live%20Demo-000000?style=for-the-badge&logo=vercel)](https://sass-scss-design-system-build51.vercel.app)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/breakingthebot/sass-scss-design-system-build51)
[![Sass](https://img.shields.io/badge/Sass-SCSS%20Modules-CC6699?style=for-the-badge&logo=sass)](file:///C:/Users/marve/Desktop/AI-286-Builds/Build_51/scss/main.scss)
[![Release](https://img.shields.io/badge/Release-v1.7.0-blue?style=for-the-badge)](file:///C:/Users/marve/Desktop/AI-286-Builds/Build_51/CHANGELOG.md)

---

## 🌟 Overview

**ApexUI** is a standalone, enterprise-grade **Sass/SCSS Design System & UI Component Infrastructure** built to showcase production SCSS architecture for modern web applications. Featuring structured design token variables, media query mixins, Sass map functions, `@each` theme token generators, code inspectors, release timelines, pricing cards, form controls, system alert callouts, analytics chart widgets, component stylesheets, and zero JavaScript dependencies.

### 🌐 Live Production Demo
- **Live Vercel Application**: [https://sass-scss-design-system-build51.vercel.app](https://sass-scss-design-system-build51.vercel.app)
- **GitHub Codebase**: [https://github.com/breakingthebot/sass-scss-design-system-build51](https://github.com/breakingthebot/sass-scss-design-system-build51)

---

## 📂 SCSS Directory Architecture

```
Build_51/
├── scss/
│   ├── abstracts/
│   │   ├── _variables.scss      # Design tokens (Indigo/Slate palette, spacing scale, breakpoints map)
│   │   ├── _mixins.scss         # Media query @mixin respond-to, @mixin glass-card, @mixin flex-align
│   │   ├── _functions.scss      # rem() and em() pixel calculation functions
│   │   └── _themes.scss         # SCSS @each theme token map iteration loop
│   ├── base/
│   │   ├── _reset.scss          # Box-sizing, accessibility reset & state hacks
│   │   └── _typography.scss     # Google Fonts (Inter, Outfit, Fira Code) & gradient text
│   ├── components/
│   │   ├── _navbar.scss         # Sticky navbar & mobile toggle drawer
│   │   ├── _buttons.scss        # Button primary, secondary, outline mixins
│   │   ├── _hero.scss           # Enterprise hero section & code inspector
│   │   ├── _cards.scss          # Metric dashboard widgets & feature cards
│   │   ├── _design-tokens.scss # Color swatch grid inspector
│   │   ├── _charts.scss         # Pure SCSS bar graph & analytics chart widget
│   │   ├── _codebox.scss        # Tabbed SCSS source code inspector box
│   │   ├── _alerts.scss         # System alert callouts & toast streamer component
│   │   ├── _forms.scss          # Enterprise text inputs, selects, input groups & toggle switches
│   │   ├── _pricing.scss        # SaaS subscription pricing cards grid
│   │   ├── _timeline.scss       # Interactive release timeline & history component
│   │   ├── _data-table.scss    # Customer deployment records data table
│   │   └── _modals.scss         # Zero-JS :target documentation inspect modals
│   └── main.scss                # Primary entrypoint compiling cleanly to css/style.css
├── css/
│   └── style.css                # Clean compiled CSS output
├── index.html                   # Enterprise HTML5 landing page
└── package.json                 # Sass compilation build scripts
```

---

## 🔥 Key Highlights

- **🎯 Standalone Professional Application**: Designed specifically for enterprise UI engineering teams.
- **📜 SCSS Release Timeline**: Interactive version timeline with pseudo-element gradient connectors and glowing hover node dots.
- **🏷️ Subscription Pricing Cards**: Responsive SaaS pricing plan grid with popular plan badges, feature checkmarks, and CTA buttons.
- **📝 Form Controls & Input Groups**: Styled text inputs, select dropdowns, input addon groups, and toggle switches with focus ring states.
- **🔔 SCSS System Alerts & Toast Banners**: Status callout banners (`.alert-success`, `.alert-warning`, `.alert-danger`, `.alert-info`) and fixed toast streamer with `@keyframes toastProgress`.
- **📋 SCSS Code Inspector Box**: Tabbed SCSS source inspector component displaying live code snippets for `_variables.scss`, `_mixins.scss`, and `_themes.scss`.
- **📊 SCSS Analytics & Bar Chart Component**: Data visualization widget with custom property height variables and hover value tooltips.
- **🎨 SCSS @each Theme Generator**: Dynamically iterates over `$themes` maps to generate `.theme-dark`, `.theme-light`, and `.theme-cyber` classes.
- **⚡ 0kb JS Executable Overhead**: 100% Pure CSS interactivity — zero script tags, zero framework runtimes.
