# 🌌 100 3D Web Elements

### The Ultimate 2.5D Spatial UI Library
A massive, production-grade collection of **100 interactive web components** engineered for a tactile, physical feel. Built with **React**, **Tailwind CSS**, and **Framer Motion**, focusing on 100% hardware-accelerated performance without WebGL.

![Status](https://img.shields.io/badge/Status-100%2F100_Complete-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

---

## ✨ Design Philosophy: "Invisible Polish"

This repository is built on the principle of **2.5D Spatial Design**. By manipulating the Z-axis, perspective, and spring physics, we create UI elements that feel like physical objects rather than flat pixels.

- **🎯 Tactile Feedback:** Every interaction has weight, inertia, and momentum.
- **⚡ GPU Accelerated:** 100% DOM manipulation using `translate3d`, `scale3d`, and `rotate`.
- **🧪 Zero Dependencies:** Runs directly in the browser via ESM CDN imports.

---

## 📂 Component Directory (1-100)

### 🛸 Immersive Backgrounds & Ambience
| # | Component | Description |
|---|---|---|
| 80 | [Fluid Mesh Gradient](components/80-fluid-mesh-gradient/background.html) | Iridescent liquid silk shifting under glass. |
| 81 | [Cyber-Grid Background](components/81-cyber-grid-background/background.html) | Topographical gravity wells in a digital grid. |
| 96 | [Aurora Mesh + Noise](components/96-aurora-mesh-noise/aurora.html) | Procedural aurora with SVG film grain overlay. |
| 97 | [Prismatic Volumetric Beams](components/97-prismatic-volumetric-beams/beams.html) | Hardware-accelerated light rays with prismatic fractures. |
| 99 | [Obsidian Glow Surface](components/99-obsidian-glow-surface/surface.html) | Dark frosted glass with a reactive magma core. |
| 100 | [Grainy Analog Shadows](components/100-grainy-analog/analog.html) | Tactile lo-fi noise with heavy lagging physical shadows. |

### 🛰️ Spatial Scrollytelling & UX
| # | Component | Description |
|---|---|---|
| 82 | [Smooth Scroll Wrapper](components/82-smooth-scroll-wrapper/scroll.html) | Inertia-based scroll hijack with spring dampening. |
| 83 | [Parallax Depth Map](components/83-parallax-depth-map/parallax.html) | Multi-layered Z-index depth diorama. |
| 86 | [Velocity Skew Grid](components/86-velocity-skew-grid/grid.html) | Images that physically lean in the direction of scroll. |
| 93 | [Smartphone App Showcase](components/93-horizontal-scroll-hijack/hijack.html) | Vertical scrollytelling phone simulator with layered UI apps. |
| 91 | [Scrubbable Scroll Text](components/91-scrubbable-scroll-text/text.html) | Kinetic typography that reveals as you scroll. |

### 🔮 High-End Micro-Interactions
| # | Component | Description |
|---|---|---|
| 74 | [Command Palette (⌘K)](components/74-command-palette/palette.html) | Immersive search overlay with gliding highlights. |
| 79 | [AI Neural Field Input](components/79-floating-label-input/input.html) | Floating label with rotating conic-gradient mask & star particles. |
| 84 | [Magnetic Blend Cursor](components/84-magnetic-blend-cursor/cursor.html) | Velocity-driven "stretch & squash" cursor with mix-blend logic. |
| 88 | [Dynamic Island CTA](components/88-peeking-cta/cta.html) | Morphing toolbar that reacts to scroll velocity. |
| 94 | [Liquid Circular HUD](components/94-sticky-mask-reveal/mask.html) | Radial clip-path expansion menu from any click coordinate. |

### 🏛️ Architecture & Data
| # | Component | Description |
|---|---|---|
| 70 | [Spatial Bento Grid](components/70-spatial-bento-grid/bento-grid.html) | Interactive layout-morphing tiles with hover elevation. |
| 76 | [Spatial Table Row](components/76-spatial-table-row/table.html) | Inline spreadsheet row expansion with background recession. |
| 90 | [Spotlight Tracking Grid](components/90-svg-scroll-border/border.html) | 6-card SaaS pricing grid with physical mouse-tracking illumination. |
| 98 | [Architectural Blueprint](components/98-architectural-blueprint/blueprint.html) | Faint grid with dynamic measurement lines and coordinate tracking. |

> [!TIP]
> **View all 100 components** in the [components/](components/) directory. Each folder is a self-contained ecosystem.

---

## 🚀 Quick Start

### 1. Serve Locally
Start a local server to view the components. You can use any of these methods:

```bash
# Using live-server (Recommended)
npx -y live-server --port=8000

# Using Python
python -m http.server 8000
```

### 2. Access
Visit: `http://localhost:8000/components/[number-name]/[file].html`

---

## 📁 Project Structure

```text
3DWebElements/
├── components/          # All 100 self-contained components
│   ├── 01-3d-button/
│   ├── ...
│   └── 100-grainy-analog/
├── styles/              # Global design system & tokens
├── .vscode/             # Pre-configured developer tasks
├── index.html           # Main showcase gallery
└── README.md            # You are here
```

---

## 🛑 Stop Server

Press `Ctrl+C` in the terminal window to stop the dev server.

---

*Hand-crafted by Saadi with 2.5D Physical Intent.*
