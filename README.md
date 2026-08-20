# Fattakse encrypted documentation portal

This public repository hosts a client-side encrypted documentation bundle for GitHub Pages.

- `index.html` contains only the encrypted payload and its browser-based unlock screen.
- Plaintext documentation and the unlock passphrase are intentionally not stored in this repository.
- Search engines are asked not to index the site, but confidentiality relies on the strong encryption passphrase—not on repository obscurity.

The portal is generated from the canonical project documentation and published as a static artifact.

## Reader experience

- Responsive desktop, tablet, and mobile layouts
- Persistent light and dark themes
- Distraction-free reading mode with adjustable type size
- Full-text search, per-document table of contents, reading progress, and previous/next navigation
- Self-contained Mermaid flowcharts with zoom, fullscreen, and SVG download controls
- Accessible keyboard navigation and print-friendly output
