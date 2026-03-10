# Perlin Noise 3D Terrain Generator

Three.js square-base terrain generator using 3D Simplex (Perlin-style) noise with parametric controls and OBJ export.

## Run

Open `index.html` in a browser (use a local server if loading ES modules: `npx serve .` or `python3 -m http.server`).

## Controls

- **Size** — Side length of the square terrain (world units).
- **Resolution** — Grid segments per side (higher = more detail, slower).
- **Noise scale** — Frequency of the noise (smaller = smoother, larger = more detail).
- **Height** — Vertical displacement scale.
- **Octaves** — Number of noise layers (more = finer detail).
- **Persistence** — Amplitude falloff per octave (0.2–0.8).
- **Lacunarity** — Frequency multiplier per octave.
- **Seed** — Integer seed for reproducible terrain.

**Download OBJ** exports the current terrain mesh as a `.obj` file (Y-up, ready for 3D apps).

## Interaction

- Drag to orbit, scroll to zoom.
