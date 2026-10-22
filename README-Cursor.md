# Powder-Bed Support Heat Path: Motion Explainer

**Product:** Code-driven, anatomy-style motion explainer of the powder-bed support heat path. 34 seconds, 30 fps, 1,020 frames (0-1019), single-file HTML canvas.

**Live preview:** GitHub Pages from the `pages` branch (root). Entry point is `index.html`.

## Run locally
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Deep links: `index.html?f=400` (support conduction), `index.html?f=620` (qualitative comparison inset), `index.html?f=1019` (stable overview).

## Editorial rules kept
- Qualitative graphs only. No invented dimensions, materials, settings, efficiencies, certifications, or performance gains.
- Changed scale, time compression, and slow-motion scan are labeled on screen.
- Energy ledger is illustrative width only, never percentages.
- Mechanism context: NIST powder-bed fusion page. Camera, palette, timing, and geometry are original illustration, not validated observation.
- Safeguard copy is on the page. This is not operating instructions for hazardous equipment.

## Files
- `index.html` : the explainer (single file, no build step)
- `medium-article-Cursor.md` : full SEO Medium article, ready to paste into Medium

## Repurposing
Swap the part/support schematic and keep the five-act frame map for laser-welding fixturing, sintering setters, or battery-tab cooling explainers.
