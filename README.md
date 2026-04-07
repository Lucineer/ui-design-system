# Cocapn Fleet UI Design System

You build agent interfaces. They need a consistent, calm, and ownable foundation. This is the shared baseline used across the fleet—a set of static assets you fork and own.

---

## Why this exists
Teams building on Cocapn were repeatedly rebuilding the same core components. This standardizes the foundational layer: buttons, forms, and layouts. It’s a single, static stylesheet with no dependencies.

---

## Quick Start
1.  **Fork this repository.** You will modify your own copy.
2.  Host the `/static` directory on any static file service (e.g., Cloudflare Pages, Vercel, NGINX).
3.  Edit the 12 CSS custom properties in `/static/theme.css` for your brand colors and link the stylesheet in your HTML.

## What you get
*   No `npm`, builds, or tooling. It's vanilla CSS that works in modern browsers.
*   A fork-first workflow. You control the source; no upstream updates will change your interface.
*   A dark-theme foundation. All colors are calibrated for extended use and meet WCAG contrast guidelines.
*   Minimal footprint. ~11kb of uncompressed CSS. No JavaScript.

## Components & Assets
*   12 root CSS variables for theming.
*   Styled base components: buttons, cards, form inputs, modals, and menus with interactive states.
*   A set of consistent SVG icons.
*   Subtle, non-competing background patterns.
*   All assets are local; no external network requests are required.

## A Starting Point, Not a Library
This is not a package you install. It is a starting point you fork and modify indefinitely. You control every border radius, color, and component. You will not receive versioned updates unless you pull them manually.

**An honest limitation:** It is a static design system. If you need complex client-side interactivity (e.g., a full component framework with state), you must build that layer yourself. This provides the visual foundation.

## Live Preview
See all components and styles in the fleet directory:
👉 https://the-fleet.casey-digennaro.workers.dev/ui

## Contributing
Contributions for accessibility improvements, bug fixes, and documentation are welcome. This is maintained by the fleet, for the fleet.

## License & Attribution
MIT License.

Attribution: Superinstance & Lucineer (DiGennaro et al.).

---

<div align="center">
  <a href="https://the-fleet.casey-digennaro.workers.dev">The Fleet</a> • <a href="https://cocapn.ai">Cocapn</a>
</div>