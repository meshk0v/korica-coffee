# Korica — Coffee Shop Website

A modern, responsive one-page website for a cozy coffee shop. Minimal design, warm colors, no frameworks and no build step.

## Sections

- **Hero** — headline, call-to-action buttons and an animated coffee cup
- **Drinks menu** — tabbed categories (classic, signature, tea & more) with prices
- **Popular items** — product cards with prices and portion sizes
- **About** — the shop's story and key features
- **Contacts** — address, opening hours with a live "open / closed" status, phone, email and an embedded map

## Features

- Fully responsive layout (desktop, tablet, mobile) with a burger menu
- Pure HTML, CSS and vanilla JavaScript
- Inline SVG illustrations, so there are no external images
- Scroll-reveal animations that respect `prefers-reduced-motion`
- Accessible tabs and navigation (ARIA attributes, keyboard support)

## Getting started

Clone the repository and open `index.html` in your browser:

```bash
git clone https://github.com/meshk0v/korica-coffee.git
cd korica-coffee
xdg-open index.html   # or just double-click the file
```

## Project structure

```
├── index.html   # page markup
├── styles.css   # styles and responsive rules
└── script.js    # menu tabs, mobile nav, animations, open/closed status
```

## Customization

The shop name, address, phone, email and prices are placeholders. Edit them in `index.html`. Colors and fonts are defined as CSS variables at the top of `styles.css`.
