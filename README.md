# 🌌 100+ High-Performance 3D Web Elements

### The Ultimate 2.5D Spatial UI Library for Modern Web Apps
A massive, production-grade collection of **100+ interactive 3D web components** engineered for a tactile, physical feel. Built with **React**, **Tailwind CSS**, and **Framer Motion**, focusing on 100% hardware-accelerated performance without WebGL.

![Hero Image](hero.png)

[![GitHub Stars](https://img.shields.io/github/stars/IntelliSaad/100-3d-web-elements?style=for-the-badge&color=ffd700)](https://github.com/IntelliSaad/100-3d-web-elements/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/IntelliSaad/100-3d-web-elements?style=for-the-badge&color=7f8c8d)](https://github.com/IntelliSaad/100-3d-web-elements/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)](LICENSE)
![Status](https://img.shields.io/badge/Status-100%2F100_Complete-00c853?style=for-the-badge)

---

## 📖 Table of Contents
- [✨ Key Features](#-key-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📂 Component Directory](#-component-directory)
  - [🛸 Immersive Backgrounds](#-immersive-backgrounds)
  - [🛰️ Scrollytelling & UX](#-scrollytelling--ux)
  - [🔮 Micro-Interactions](#-micro-interactions)
  - [🏛️ Architecture & Data](#-architecture--data)
- [🚀 Quick Start](#-quick-start)
- [🎨 Design Philosophy](#-design-philosophy)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## ✨ Key Features
- **🎯 100% Tactile:** Every interaction has weight, inertia, and physical momentum.
- **⚡ Zero WebGL:** Runs entirely on the DOM using `translate3d`, `scale3d`, and `rotate` for 60FPS locking on 8GB RAM machines.
- **🌈 Modern Aesthetics:** Glassmorphism, iridescent gradients, and procedural noise filters.
- **🚀 ESM Ready:** No build step required. Imports directly from ESM-CDNs for rapid prototyping.

---

## 🛠️ Tech Stack
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

---

## 📂 Component Directory (1-100)

### 🛸 Immersive Backgrounds & Ambience
*High-performance backgrounds that react to user presence and environmental shifts.*
| # | Component | Primary Tech | Highlight |
|---|---|---|---|
| 81 | [Cyber-Grid Background](components/81-cyber-grid-background/background.html) | HTML5 Canvas | Topographical gravity wells. |
| 96 | [Aurora Mesh + Noise](components/96-aurora-mesh-noise/aurora.html) | CSS Keyframes | Procedural film grain overlay. |
| 97 | [Prismatic Volumetric Beams](components/97-prismatic-volumetric-beams/beams.html) | SVG Masking | Hard-light light rays. |
| 99 | [Obsidian Glow Surface](components/99-obsidian-glow-surface/surface.html) | Backdrop Filter | Reactive violet magma core. |

### 🛰️ Scrollytelling & 2.5D UX
*Interactions that use the scroll wheel as a physical lens.*
| # | Component | Primary Tech | Highlight |
|---|---|---|---|
| 82 | [Smooth Scroll Wrapper](components/82-smooth-scroll-wrapper/scroll.html) | Framer Motion | Inertia-based scroll hijack. |
| 86 | [Velocity Skew Grid](components/86-velocity-skew-grid/grid.html) | useVelocity | Physical image "leaning" physics. |
| 93 | [Smartphone App Showcase](components/93-horizontal-scroll-hijack/hijack.html) | Z-Axis Masking | Layered scrollytelling phone tour. |

### 🔮 High-End Micro-Interactions
*Micro-elements that provide immediate tactile satisfaction.*
| # | Component | Primary Tech | Highlight |
|---|---|---|---|
| 74 | [Command Palette (⌘K)](components/74-command-palette/palette.html) | LayoutId | Gliding highlight physics. |
| 79 | [AI Neural Field Input](components/79-floating-label-input/input.html) | Conic Gradient | Star particle typing eruption. |
| 84 | [Magnetic Blend Cursor](components/84-magnetic-blend-cursor/cursor.html) | useSpring | Squash-and-stretch velocity cursor. |

---

## 🎨 Design Philosophy: "Physical Intent"
We move away from digital flatland. Every component in this library exists in a simulated **3D space**. 
- **Z-Axis Depth:** Elements cast physical shadows and have architectural height.
- **Spring Physics:** No linear tweens. We use `stiffness`, `damping`, and `mass` to define how objects move.
- **Optical Refraction:** We simulate glass and light using `backdrop-filter` and `mix-blend-mode`.

---

## 🚀 Quick Start
### 1. View locally
```bash
# Start a local server (any method works)
npx -y live-server --port=8080
```
### 2. Implementation
All components are self-contained. Simply copy the `html` file or the specific `React` logic into your project. All dependencies (Tailwind, Framer Motion) are loaded via CDN.

---

## 🤝 Contributing
Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

