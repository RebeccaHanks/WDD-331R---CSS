# WDD 331R Practice Site

**Student:** Rebecca Hanks  
**Semester:** Semester 10 - Year 4  

## Live Site

[View Site](https://your-username.github.io/your-repo-name/)

---

## About

This repository is my Practice Site for WDD 331R: Advanced CSS.

The site uses a layered CSS architecture with design tokens, reusable components, and a shared stylesheet bundled with Lightning CSS.

The site automatically deploys to GitHub Pages through GitHub Actions.

---

## Folder Structure

```txt
css/
├── base/
├── components/
├── layout/
├── tokens/
├── utilities/
└── main.css

dist/
└── styles.css
```

- `tokens/` → design tokens like colors and spacing
- `base/` → reset and HTML element styles
- `components/` → reusable UI components
- `layout/` → overall page layout
- `utilities/` → helper utility classes

---

## Build Tool

This project uses **Lightning CSS** to:

- bundle imported CSS files
- process native CSS nesting
- minify production CSS

---

## Commands

Install dependencies:

```bash
npm install
```

Build CSS:

```bash
npm run build
```

Watch CSS during development:

```bash
npm run watch
```

---

## Pages

- [Home](index.html)
- [Custom Properties and Nesting](unit-1/custom-properties/index.html)
- [Layered Components](unit-2/layered-components/index.html)

## Dark Mode Support

This site supports light mode, dark mode, and system theme preferences using modern CSS color tokens and semantic design tokens.

Color tokens are organized in:

- `css/tokens/colors.css`
- `css/tokens/variables.css`

The color system uses:
- seed tokens
- semantic tokens
- accent ramps
- `light-dark()` theme switching

Theme selection is controlled through a CSS-based theme toggle component.

- [Editorial Layout](unit-4/grid-layouts/editorial.html)
- [Card Grid](unit-4/grid-layouts/cards.html)