<div align="center">

# 🔷 Pattern Studio

**Turn any photo into a seamless tile pattern — in your browser.**

[![Open Tool](https://img.shields.io/badge/▶_Open_Tool-2d6cdf?style=for-the-badge&logoColor=white)](https://nullmar.github.io/pattern/)




</div>

---

## ✨ What it does

Drop a photo, pick a symmetry pattern, export a seamless tile. From classic
wallpaper symmetry groups to modern aperiodic tilings like Penrose and Truchet.

**[→ Try it live](https://nullmar.github.io/pattern/)**

---

## 🎯 Features

| | |
|---|---|
| ⬢ **18 pattern types** | Hexagon (6/12 sectors), square, triangle, kaleidoscope, mirror, grid, glide, pmm, Penrose, hat, pinwheel, Truchet, moiré, Voronoi |
| 🎨 **7 background modes** | Checker, solid color, blur, edge (whole / region-aware), mirror (whole / region-aware) |
| 📐 **Source shape preview** | Blue outline shows exactly what part of the photo becomes a tile |
| 🎚️ **Live controls** | Scale, rotation, tile size — all with instant preview |
| 💾 **Export** | PNG (transparent), JPEG, TGA. Up to 4096px |
| 🔒 **100% client-side** | Nothing is uploaded — everything runs in your browser |

---

## 🖼️ Screenshots

<div align="center">

<table>
<tr>
<td width="50%">

**Hexagon**
<img src="screens/pattern_1005x1044 (1).png" width="100%">

</td>
<td width="50%">

**Kaleidoscope**
<img src="screens/pattern_1005x1044.png" width="100%">

</td>
</tr>

</table>

</div>

> 💡 Замени пути к картинкам на свои. Если скриншотов нет — просто удали эту секцию.

---

## 🚀 How to use

1. **Open** [Pattern Studio](https://nullmar.github.io/pattern/)
2. **Drop** a photo (or press `Ctrl+V`)
3. **Pick** a pattern from the dropdown
4. **Drag** inside the *Source* preview to choose which part of the photo becomes a tile
5. **Adjust** scale, rotation, tile size
6. **Export**

---

## 🧩 Pattern types

<details>
<summary><b>Symmetry groups (12)</b></summary>

- **Hexagon (6 sectors)** — classic 6-fold snowflake symmetry
- **Hexagon 12** — finer 12-sector version
- **Square 8** — 8-fold rhombus symmetry
- **Square 4** — 90° rotation
- **Triangle 6** — 6-sector triangular lattice
- **Triangle 12** — 12-sector triangular lattice
- **Kaleidoscope** — 8 mirrors around center
- **Mirror 2×2** — simple 4-way reflection
- **Grid** — plain tiling, no mirrors
- **Rotation 180°** — point symmetry
- **Glide reflection** — shifted mirror
- **Rectangular (pmm)** — reflections across both axes

</details>

<details>
<summary><b>Aperiodic / decorative (6)</b></summary>

- **Penrose** — 5-fold quasi-symmetry
- **Hat** — monotile-inspired
- **Pinwheel** — golden-ratio spiral
- **Truchet** — randomized quarter-tile rotation
- **Moiré** — overlapping grids
- **Voronoi** — jittered cell layout

</details>

---

## 🎨 Background modes

| Mode | Description |
|------|-------------|
| **Checker** | Transparent checkerboard — outside is transparent in PNG |
| **Solid color** | Fill outside with a solid color (from palette or custom) |
| **Blur** | Blurred, stretched copy of the photo |
| **Edge (whole)** | Stretch outermost pixels of the whole photo |
| **Edge (region)** | Stretch outermost pixels of what is visible in the region |
| **Mirror (whole)** | Reflect the whole photo outwards |
| **Mirror (region)** | Reflect edges of what is visible in the region |

---
