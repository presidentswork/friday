# FRIDAY — website

Single-file site for FRIDAY (fridayapp.com), built in the Relay design system: black page, lime accent, three.js particle stream, preloader, spring motion.

- `index.html` — the live page (currently v3)
- `versions/` — every delivered version, kept as-is
- `assets/friday-wordmark.svg` — the traced FRIDAY wordmark (fills with `currentColor`)

No build step. three.js and Lenis load from jsDelivr via an import map; fonts from Google Fonts.
