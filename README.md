# RITUAL PRESS

A constrained vector studio — Illustrator with way fewer tools, so everything you make
looks like the house style by construction. Built as a collaboration between Neeff and Claude,
July 2026. Cassette futurism all the way.

## Apps

- **ritual-press.html** — the editor. Open in any browser, no build, no deps.
- **liturgy-engine.html** — seeded generative ritual-poster engine in the same visual language.

## Editor concepts (v0.2)

- **Shapes, not paths** — 10 primitives incl. COMB and EYE as first-class tools.
- **Pathfinder**: KNOCK (destination-out cut), CLIP (conform inside a host shape), SOLID/FREE to undo.
- **Locked palettes** — four worlds (OWL / BUFO / MASK / TIDE); switching worlds re-inks the whole piece.
- **Textures**: flat, halftone, combed, hatch, stipple, riso grain, dry brush, aquatint (the Goya one).
- **Mask-first brushes** — stipple / grit / dry. Select a shape first and strokes are clipped
  inside it: coloring inside the lines, guaranteed. This is brushing for masking people.
- **Magnetic snapping** — edges/centers pull to neighbors and the canvas axis with guide lines.
- **J MODE** — symmetry liturgy: axis + register scaffold, every placement auto-mirrors.
- 8px grid snap, undo, 2x PNG export with paper grain.

## Roadmap

- True path booleans (real pathfinder, not compositing)
- Rotation, arc-angle control
- Save/load `.ritual` files (shape list is already clean JSON)
- Custom palette authoring (still locked at use-time)
- Glyph library as placeable stamps
- I Ching field-driven composition mode (hexagram weather picks glyphs/inks/tilt)
