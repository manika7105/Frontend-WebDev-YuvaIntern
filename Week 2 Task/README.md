# Nomad — Week 2 Responsive Web Design

Responsive travel landing page created for the Frontend Web Developer Internship Week 2 task.

## Focus
The project demonstrates flexible grids, Flexbox, CSS media queries, fluid typography, responsive images, semantic HTML, accessibility focus states, and reduced-motion support.

## Responsive breakpoints
- **Above 900px:** multi-column hero and destination layouts; three-column stories.
- **641–900px:** hero collapses to one column; destination/story grids reduce columns.
- **640px and below:** single-column cards, wrapped navigation, full-width buttons, smaller spacing and fluid heading sizes.

## Fluid images
Local SVG assets are used so the project works without third-party image hosting. Images use `width: 100%; height: auto;` and `aspect-ratio`/`object-fit` where appropriate.

## Testing
Recommended browser DevTools sizes: 1440×900, 1024×768, 768×1024, 390×844, and 360×800. Check overflow, navigation, image scaling, card stacking, typography and button usability.

## Structure
```text
Week-2-Responsive-Web-Design/
├── index.html
├── style.css
├── README.md
└── assets/
    ├── hero.svg
    ├── coast.svg
    ├── mountain.svg
    └── city.svg
```
