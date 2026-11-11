# Botanix — Herbal Nutrition Landing Page

Static recreation of the Figma design `Rootwell — Version 2 (Hi-fi)` (`G9lhBouzpBTCEguOmHKxGB`, node `148043:324`).

## Run locally

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

No build step is required: React, ReactDOM, Babel, and Tailwind are loaded from CDNs. Assets were exported from Figma into `assets/figma/`; Creato Display is self-hosted in `assets/fonts/`, and TASA Orbiter/Fustat/Instrument Serif/Inter are loaded from Google Fonts to match the Figma typography. Subtle scroll-reveal, hover lift, hero drift, and nav float motion are included with `prefers-reduced-motion` support.

## Publish

This folder is intended to be pushed as a new GitHub repository and can be served with GitHub Pages from the repository root.
