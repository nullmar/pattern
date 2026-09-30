# 🔷 Pattern Studio

**Turn any photo into a tile pattern — right in your browser.**

[![Open Tool](https://img.shields.io/badge/▶_Open_Tool-2d6cdf?style=for-the-badge&logoColor=white)](https://nullmar.github.io/pattern/)

---

## ✨ What it does

Drop a photo, pick a symmetry pattern, export a tile. Mirror-based patterns are
seamless for **any** photo; the rest are clearly marked in the list so you know
what you get before you export.

**[→ Try it live](https://nullmar.github.io/pattern/)**

---

## 🎯 Features

|                                |                                                                                                                       |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| ⬢ **20 pattern types**         | Grouped in the list: seamless / plain repeat / decorative                                                             |
| 🎨 **5 background modes**       | Checker, mirror, solid color, blur, edge — all follow scale, rotation and position                                    |
| 📐 **Source shape preview**     | The blue outline is computed from the real pattern builder, so it shows exactly which part of the photo is used       |
| 🎚️ **Live controls**           | Scale, rotation, tile size and waves with instant preview; segments/twist for Mandala, gap for Mosaic                  |
| 🎨 **Color correction**        | Brightness, contrast, saturation, hue, black & white / sepia — applied to the photo before the pattern is built, so backgrounds follow                 |
| 🔀 **Variation**               | Smooth brightness/tint drift across the pattern so repeated tiles don't look identical; tile edges still match                                          |
| 🔗 **Shareable settings**       | Everything (pattern, background, sliders, color, region) lives in the page URL `#…`; **Copy link to settings** shares it. The photo itself is not in the link |
| ⊞ **Seam check**               | One click shifts the preview by 50% so any seam shows up in the middle                                                |
| 🖱️ **Zoom & pan**              | Drag to move, mouse wheel or pinch to zoom in the Source preview; the area can't be dragged off the photo             |
| 💾 **Export**                  | PNG (transparent), JPEG, TGA at 256–4096 px, or copy to clipboard. **Repeats** as in the preview, or **one tile** of exact size that repeats seamlessly |
| 📱 **Works on phones**          | Layout follows the real visible height (no cut-off Save button), tap the `?` icons for hints                          |
| 🔒 **100% client-side**         | Nothing is uploaded — everything runs in your browser                                                                 |

---

## 🚀 How to use

1. **Open** [Pattern Studio](https://nullmar.github.io/pattern/)
2. **Drop** a photo (or press `Ctrl+V`, or use the paste button)
3. **Pick** a pattern from the dropdown
4. **Drag** inside the *Source* preview to choose which part of the photo becomes a tile
5. **Adjust** scale, rotation, tile size
6. **Export**

---

## 🧩 Pattern types

**Seamless — tile edges match for any photo (12)**

- **Hexagon (6 sectors)** — classic 6-fold symmetry on a hex lattice
- **Hexagon 12** — finer 12-sector version
- **Square 8** — 8-fold rhombus symmetry
- **Square 4 (mirrored)** — 4-fold symmetry with reflections
- **Triangle 6 / Triangle 12 (no stretch)** — triangular sectors taken from the photo without distortion
- **Kaleidoscope** — 8 mirrors around the center
- **Mirror 2×2** — simple 4-way reflection
- **Diamond mirror (cmm)** — reflections on a diamond grid
- **Rectangular (pmm)** — reflections across both axes
- **Moiré (mirror layers)** — two overlapping mirrored grids
- **Grid (seamless blend)** — plain repeat, but the tile is cross-faded with a half-shifted copy so any photo tiles (slight ghosting at the edges)

**Plain repeat — seams depend on the photo (2)**

- **Grid** — plain tiling, no mirrors
- **Glide rows** — alternating flipped rows (visible seams between rows)

**Decorative (6)**

- **Truchet tiles** — random rotation/flip of cells, edges wrap around
- **Voronoi collage** — jittered, rotated cells, edges wrap around
- **Mandala (medallion)** — radial mirror medallion with adjustable **Segments** (4–24) and **Twist**; edges don't tile
- **Mosaic — circles / rounded squares / hexagons** — the photo in cells with an adjustable **Gap**, gap color or transparent gap; tiles seamlessly as a lattice

---

## 🎨 Background modes

What fills the area outside the photo when the selected region goes past its edges.

| Mode                     | Description                                                              |
| ------------------------ | ------------------------------------------------------------------------ |
| **Checker**              | Transparent — the checkerboard is preview only, PNG stays transparent    |
| **Mirror (reflect borders)** | The photo is reflected outward at its borders                        |
| **Solid color**          | Fill with a solid color (from the palette or custom)                     |
| **Blurred image**        | Soft blurred copy of the photo                                           |
| **Edge (stretch borders)** | Outermost pixels of the photo are stretched outward                    |

Mirror and Edge follow the photo's scale, rotation and position, so the fill
always lines up with the photo itself.

---

## 🛠️ Notes

- Single file (`index.html`), no dependencies, no build step.
- Very large exports (4096) are heavy: on phones the tab may run out of memory — pick a smaller size if saving fails.
