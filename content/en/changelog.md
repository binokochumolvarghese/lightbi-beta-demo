---
title: "Changelog"
date: 2019-01-01
subtitle: "Theme updates and improvements, listed in reverse chronological order."
type: page
---

#### Jun 2026

- **Pagefind search** — replaced Lunr.js with [Pagefind](https://pagefind.app/) for static, zero-JS-bundle search. Added `Ctrl+K` / `Cmd+K` keyboard shortcut to open the search modal.
- **Proper dark mode** — replaced the `filter: invert()` CSS hack with a full CSS custom property system under `[data-theme="dark"]`. All Bootstrap components (cards, borders, links, text) adapt automatically via `--bs-*` variable overrides.
- **Playfair Display headings** — added [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) as the heading font across all `h1`–`h6` elements, with responsive `clamp()` sizing for post headings.
- **Tag pills** — tags on post pages now render as styled pill badges (`.tag-pill`) with a subtle border, matching modern blog conventions.
- **Post navigation buttons** — replaced solid `btn btn-dark` prev/next buttons with rounded pill-style `.nav-post-btn` links with light/dark mode variants and a hover lift effect.
- **Post heading layout** — individual post pages now show a `← section` breadcrumb above the title, date-only meta row below it (author name removed). Heading is left-aligned and matches the article column offset precisely, including when a Table of Contents sidebar is present.
- **ToC alignment fix** — tags, share card, and prev/next navigation sections now correctly follow the article column offset (`offset-lg-1` when ToC is visible, `offset-lg-2` otherwise).
- **Share card improvements** — added `border rounded-4` to the "What are your thoughts" card; icon and heading are now vertically aligned; fixed missing closing `</div>` tags.
- **Copy button on code blocks** — added a floating "Copy" button to all highlighted code blocks, with a "Copied!" confirmation state.
- **Anchor links on headings** — headings inside blog posts get a `#` anchor link on hover for easy deep-linking.
- **Font size normalisation** — body font reduced from `1.2rem` to `1rem`; `.post-entry` and `.nav-link` sizes adjusted accordingly.
- **Dark mode bug fixes** — fixed white navbar language-switcher button, white "What are your thoughts" card, and black notes text in dark mode.
- **Special pages** — added Changelog, Credits, Disclaimer, Uses, Now, and For pages to the demo site. Added a **More** dropdown in the navigation and footer page links.
- **404 page** — added a styled 404 layout to the theme.
