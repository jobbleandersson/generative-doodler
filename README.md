# Generative Art Doodler

A single-file, zero-dependency generative art toy. Click and drag on the canvas to
spray particles that drift through an animated flow field. Faster strokes spray wider.
Everything runs locally in your browser — nothing is uploaded.

## Run it

Open `index.html` in any modern browser. That's it.

Or serve the folder if you prefer a local server:

```bash
python -m http.server
# then visit http://localhost:8000
```

## Controls

- **Palette** — pick one of six color sets for new particles.
- **Physics**
  - *Gravity* — vertical pull on particles (negative values push up).
  - *Turbulence* — how strongly the flow field bends particle paths.
  - *Spray rate* — particles emitted per frame while painting.
  - *Particle life* — how long particles live before fading out.
  - *Size* — base particle radius.
- **Canvas**
  - *Fade trails* — slowly fade the canvas each frame for a trailing look.
  - *Glow* — additive blending so overlapping particles brighten.
- **Clear** — remove all particles and repaint the background.
- **Cycle BG** — step through the background colors.
- **Save PNG** — download the current canvas as an image.

## License

No license specified yet.
