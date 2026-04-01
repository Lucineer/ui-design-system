# UI Design System — Premium Dark Theme for Cocapn Ecosystem

> *One design system. Every app. Easily customizable by agents.*

## What This Is

A complete dark-theme design system built for the cocapn ecosystem. Every cocapn vessel, useful app, and deckboss cell can use this as a starting point and customize it for their users.

## Files

- `design-system.html` — Full component library (buttons, inputs, cards, badges, avatars, tabs, sidebar, modals, toasts, dropdowns, toggles, progress, skeletons, chat bubbles, code blocks, tooltips, animations)
- `backgrounds.html` — 6 premium app backgrounds (Deep Space, Northern Lights, Carbon Fiber, Ocean Depth, Volcanic, Forest Floor)
- `menu-system.html` — 8 navigation patterns (tab bar, hamburger, command palette, context menu, dropdown, breadcrumbs, pill nav, segmented control)
- `mockups/` — AI-generated app mockups for each product

## How Agents Use This

1. **Starting point**: Copy the CSS custom properties into your app
2. **Customize**: Change the primary color, spacing, typography to match your vessel
3. **Extend**: Add vessel-specific components on top of the base system
4. **Per-user**: The agent can tweak colors, density, and layout based on user preferences

## Integration

The design system is pure CSS — no dependencies, no build step. Copy what you need, customize the rest.

```css
/* Change the primary color for your vessel */
:root {
  --color-primary-500: #0ea5e9;  /* Teal for PersonalLog */
  --color-primary-500: #a855f7;  /* Purple for Cocapn */
  --color-primary-500: #c9a23c;  /* Gold for DMLog */
  --color-primary-500: #10b981;  /* Emerald for FishingLog */
}
```

## Background System

Each app can choose a background that matches its personality:
- PersonalLog: Ocean Depth (calm, personal)
- MakerLog: Carbon Fiber (technical, precise)
- DMLog: Deep Space (immersive, mysterious)
- FishingLog: Forest Floor (organic, outdoor)
- Deckboss: Northern Lights (dynamic, connected)

## Design Principles

- Dark first (#0a0a0a base)
- Minimal chrome — content is king
- Subtle animations — never distracting
- System fonts — fast, native feel
- 4px base grid — consistent spacing
- Mobile-first responsive

Author: Superinstance
