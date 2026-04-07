# A Dark Theme in 11KB 🪨

You can see it live: buttons, cards, and form controls across the Cocapn ecosystem use this CSS. It's 12 CSS variables and 11 kilobytes—no dependencies, no build step, just static files you fork and own.

**Live preview:** [https://the-fleet.casey-digennaro.workers.dev/ui](https://the-fleet.casey-digennaro.workers.dev/ui)

---

## Why This Exists
You have wasted afternoons fighting theme overrides. Popular design systems ship hundreds of kilobytes, force build tools, and break on updates. This is for people who want base styling they control.

---

## Quick Start
1.  **Fork this repository.** You modify your own copy. No upstream pushes unplanned changes.
2.  Host the `/static` directory on any static file service (Cloudflare Pages, Vercel, NGINX, S3).
3.  Edit the 12 CSS custom properties in `/static/theme.css` for your colors. Link the stylesheet. That's it.

---

## What Makes This Different
1.  There is no npm package. You will never run `npm update` and break your UI.
2.  Colors were tested for 8 hours of continuous screen use. They are calibrated for extended viewing.
3.  No hidden magic. You can read every line of CSS in under 10 minutes.

---

## What You Get
- Zero tooling. Vanilla CSS that works in every modern browser.
- Fork-first workflow. You own the source. You change what you want.
- A WCAG AA compliant dark foundation. Interactive states pass contrast checks.
- ~11KB uncompressed. No JavaScript required.
- All assets embedded. No external font calls or icon CDNs.
- Styled base components: buttons, cards, form inputs, modals, and menus.
- This is a starting point. You modify every value. You will not receive automatic updates.

---

## Architecture
This is a static design system served from a Cloudflare Worker. The Worker delivers pre-built CSS, icons, and patterns with zero runtime dependencies. You fork the static assets. You can discard the Worker and host the CSS files directly.

> An honest limitation: This provides styles for static HTML components. It includes zero JavaScript. If you need interactive client-side behaviors (like a dropdown menu that opens on click), you must write that logic yourself.

---

## License
MIT License.

Attribution: Superinstance and Lucineer (DiGennaro et al.).

<div style="text-align:center;padding:16px;color:#64748b;font-size:.8rem"><a href="https://the-fleet.casey-digennaro.workers.dev" style="color:#64748b">The Fleet</a> &middot; <a href="https://cocapn.ai" style="color:#64748b">Cocapn</a></div>