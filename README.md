# UI Design System 🖤

You shouldn't have to rebuild every button every time you spin up a new agent.

This is the official dark theme design system for the Cocapn Fleet. It provides a shared baseline for agent interfaces, built because teams were spending time on repetitive styling instead of core agent logic. Fork it to create your own starting point.

---

## Quick Start

1.  **Fork** this repository.
2.  Deploy the `/static` directory to any static host (Cloudflare Pages, Vercel, etc.).
3.  Modify the root CSS variables in `/static/theme.css` for your brand, then link to it in your HTML.

---

## What You Get

*   **Dark theme:** A color palette calibrated for readability with 12 core CSS custom properties.
*   **Component styles:** Pre-built CSS for buttons, cards, inputs, modals, and menus, including interactive states.
*   **Static assets:** A set of SVG icons and background patterns.
*   **Zero dependencies:** Vanilla CSS with no build step, framework, or npm packages.
*   **Fleet-native:** Styles are tested for compatibility with the Cocapn agent runtime.

---

## What Makes This Different

This is a design system you own, not a library you import. You fork it once and modify it indefinitely.

*   **No forced updates:** You will never receive a breaking change. Integrate upstream improvements only if you choose to.
*   **No abstractions:** Every line of CSS and SVG is in your control.
*   **Local-first:** Everything works offline after download; no external CDN is required.

**Limitation:** As a static CSS system, dynamic theme switching (e.g., light/dark mode) requires manual implementation on your part.

---

## Try It

Preview the component library live:  
[https://the-fleet.casey-digennaro.workers.dev/ui](https://the-fleet.casey-digennaro.workers.dev/ui)

---

## Architecture

This repository contains only static assets—plain CSS, SVG files, and HTML examples. It is designed to be forked and extended, serving as a centralized reference for foundational UI patterns within the fleet.

---

## Contributing

Discussions and pull requests for core accessibility improvements, documentation, or bug fixes are welcome.

---

## License & Attribution

MIT License.  
Created as part of the Cocapn Fleet.  
Attribution: Superinstance & Lucineer (DiGennaro et al.).

---

<div align="center">
  <a href="https://the-fleet.casey-digennaro.workers.dev">The Fleet</a> • <a href="https://cocapn.ai">Cocapn</a>
</div>