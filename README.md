<div align="center">

```
  ( (
   ) )
 ........
 |      |]
 \      /
  `----'
```

# grandmothers-mug

*A story-driven Blender tutorial — model a memory, not just a mesh.*

[![Blender](https://img.shields.io/badge/Blender-4.x-E87D0D?style=flat-square&logo=blender&logoColor=white)](https://blender.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-c0622a?style=flat-square)](LICENSE)
[![HTML Only](https://img.shields.io/badge/deps-none-8aa67a?style=flat-square)](index.html)
[![Made With](https://img.shields.io/badge/made%20with-patience-c48a8a?style=flat-square)](#)

> *"It wasn't just a model. It was my history, recreated by my hands,*
> *using a tool that cost nothing but patience."*

</div>

---

## ✦ What Is This?

An **interactive, single-file web guide** for modeling a vintage 1970s ceramic coffee mug in Blender — chipped rim, faded hand-painted flowers, warm glaze, and all the honest imperfections that make it real.

This isn't a "how to make a cup" tutorial. It's a guide to modeling *something meaningful.* The kind of object that sits in your memory, heavy with kitchen light and the smell of old mornings.

No npm. No frameworks. One `index.html` file. Open it in a browser, follow along in Blender.

---

## ✦ The Six Phases

| Phase | Name | Steps | What You'll Do |
|:-----:|------|:-----:|----------------|
| `01` | **Setup** | 3 | Clear the scene · reference image · units |
| `02` | **The Body** | 5 | Cylinder → loop cuts → silhouette → rim → foot ring |
| `03` | **The Handle** | 3 | Bézier curve → bevel → Bridge Edge Loops |
| `04` | **Soul** | 2 | Chip the rim · Subdivision Surface · Crease edges |
| `05` | **Surface** | 3 | Principled BSDF · UV unwrap · Texture Paint · age noise |
| `06` | **The Scene** | 3 | HDRI lighting · area light · camera · Cycles render |

---

## ✦ Getting Started

### Prerequisites

- [Blender 4.0+](https://blender.org) — free, always will be
- A modern browser to follow the guide
- 2–4 hours · a quiet evening helps

### Open the Guide

```bash
git clone https://github.com/your-username/grandmothers-mug.git
cd grandmothers-mug
open index.html
```

> **Tip:** One monitor for the guide. One for Blender. Each step is timed to real-world workflow — no rushing.

---

## ✦ File Structure

```
grandmothers-mug/
├── index.html              # The complete interactive tutorial (self-contained)
├── README.md               # You are here
├── assets/
│   └── reference/          # Vintage ceramic mug reference photos
└── blend/
    └── mug-final.blend     # ⚠ Spoilers — completed model
```

> **⚠ Spoiler warning:** `blend/mug-final.blend` contains the finished mug.
> Try building it yourself first. The process *is* the point.

---

## ✦ Key Shortcuts

The guide surfaces these contextually, but here's your cheat sheet:

| Action | Shortcut |
|--------|----------|
| Toggle Edit / Object mode | `Tab` |
| Loop Cut | `Ctrl` + `R` |
| Select edge loop | `Alt` + Click |
| Toggle Proportional Editing | `O` |
| Crease selected edges | `Shift` + `E` |
| UV Unwrap menu | `U` |
| Render | `F12` |

---

## ✦ The Story Behind It

Three years ago, someone was trapped by expensive software subscriptions. A friend said something simple:

> *"Just get Blender. It's free."*

Free, in the creative industry, usually means limited. But one quiet Saturday night, alone, with no plans — that person modeled their grandmother's old ceramic coffee mug. The chipped one with faded flowers from the 70s.

They started with a cylinder. Hours disappeared. No tutorial — just observation.

This guide is that night, documented.

---

## ✦ Render Checklist

Before you hit `F12`:

- [ ] Render engine set to **Cycles** (not EEVEE)
- [ ] Samples: **512+**
- [ ] Denoiser: **ON** (Intel Open Image Denoise)
- [ ] Color Management: **Filmic** · Contrast: Medium High
- [ ] Output: **PNG** · 1920×1080
- [ ] The chip catches the light
- [ ] The flowers are soft, not sharp
- [ ] The glaze has subtle variation

---

## ✦ Contributing

Contributions welcome — especially from people who've modeled something personal.

If this guide helped you recreate a meaningful object — a parent's coffee thermos, a childhood toy, a grandmother's anything — share a render in [Discussions](../../discussions). That's what this is for.

```
1. Fork the repo
2. Create a branch:  git checkout -b phase/your-improvement
3. Commit:           git commit -m 'Add: better handle bridging notes'
4. Push:             git push origin phase/your-improvement
5. Open a Pull Request
```

This project follows the [Contributor Covenant](https://www.contributor-covenant.org) Code of Conduct.
The Blender community is generous and kind — let's keep it that way.

---

## ✦ Acknowledgments

To the friend who said *"Just get Blender. It's free."*

To every stranger who posted a tutorial at 2 a.m. and never knew who they helped.

To the Blender Foundation — for believing creativity shouldn't have a subscription fee.

---

## ✦ License

**MIT** — use it, remix it, teach with it.

Just credit the strangers who post tutorials at 2 a.m.

---

<div align="center">

*From a default cube to a world.*
*From a cylinder to a memory.*

**⬡ [blender.org](https://blender.org)** · built with patience · no dependencies

</div>
