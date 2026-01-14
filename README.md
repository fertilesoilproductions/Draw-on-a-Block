# Draw on a Block

**Paint directly on 3D models with pixel-perfect precision.**

[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20PC-blue.svg)](#platforms)
[![Engine](https://img.shields.io/badge/Engine-Unity%206.2-black.svg)](https://unity.com)

---

## Overview

**Draw on a Block** is a 3D pixel art painting application for PC and mobile that lets you paint textures directly onto 3D model surfaces. Using real-time raycasting and UV mapping, your brush snaps to the exact pixel on the texture—no more switching between 2D image editors and 3D viewers.

Whether you're creating Minecraft block textures, Roblox accessories, indie game assets, or just having fun with pixel art in 3D, Draw on a Block gives you an intuitive workflow that works on your desktop or on the go.

---

## Key Features

### 🎨 Direct 3D Painting
- Paint directly on model faces with pixel-accurate brush placement
- Raycast-based input snaps to texture pixel centers
- Nearest-neighbor filtering preserves crisp pixel art at all zoom levels

### 📐 Multi-Resolution Support
- Standard sizes: 16×16, 32×32, 64×64, 128×128, 256×256
- Custom resolutions for advanced workflows
- Per-material resolution control on multi-material models

### 🗂️ Layer System
- Up to 16 layers per material
- Visibility, opacity, and blend mode controls
- Real-time compositing with transparency preview

### 🔧 Complete Toolset
| Tool | Description |
|------|-------------|
| **Brush** | Variable size painting with pressure support |
| **Line** | Pixel-perfect Bresenham lines |
| **Shapes** | Rectangle and circle (hollow/filled) |
| **Fill** | Flood fill, linear gradient, radial gradient |
| **Eraser** | Brush and face-based erasing |
| **Blend** | Smooth pixel edges with adjustable strength |
| **Selection** | Magic wand, copy/paste, flip, rotate |
| **Stamp** | Place decals and saved selections |

### 📦 Model Import
- **Supported Formats:** FBX, OBJ, glTF/GLB, Blockbench (.bbmodel)
- Auto-detect textures and resolutions from source files
- Multi-material models with independent texture stacks
- Preserve Blockbench layer structures

### 📤 Export Options
- **PNG textures** at original or scaled resolutions
- **Full model export** with painted textures (FBX, OBJ, glTF, GLB, BBModel)
- All exports licensed for personal and commercial use

### ✨ Quality of Life
- **Auto-save** every 60 seconds and on app pause
- **Full undo/redo** history for all painting actions
- **Explode view** to access hidden faces on complex models
- **Texel grid overlay** shows pixel boundaries at any zoom

---

## Platforms

| Platform | Status | Distribution |
|----------|--------|--------------|
| **Windows PC** | ✅ Supported | Steam |
| **Android** | ✅ Supported | Google Play |
| **iOS** | ✅ Supported | App Store |

---

## Target Audience

- **Minecraft Modders** — Block textures, mob skins, item sprites
- **Roblox Developers** — Avatar items, game props, accessories
- **Hytale Creators** — Voxel-style characters and environments
- **Indie Game Devs** — Rapid texture iteration without app-switching
- **Artists & Hobbyists** — 3D pixel art, dioramas, creative projects

---

## Screenshots

<img width="1546" height="830" alt="image" src="https://github.com/user-attachments/assets/df9432cb-6172-4b8a-a69a-6c5477812c84" />
<img width="1545" height="830" alt="image" src="https://github.com/user-attachments/assets/19b9e67e-618e-4997-b172-6793df6d0a7a" />
<img width="1319" height="573" alt="image" src="https://github.com/user-attachments/assets/c0dca682-2f81-4af7-8fda-a0436c0c50e5" />
<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/b14b4a35-fc14-4bef-b1e4-606c85ebe7ab" />
<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/4b789724-6d90-4de7-b222-016c2c8b52b6" />
<img width="1919" height="1033" alt="image" src="https://github.com/user-attachments/assets/a0fae733-343e-4049-8c21-a9b8270a1e49" />


---

## Pricing

| Edition | Price | Features |
|---------|-------|----------|
| **Free** | $0 | Built-in models, full painting tools, PNG export |
| **Pro Unlock** | $29 (one-time) | Custom model import, texture import, advanced export |
| **Model Kits** | Varies | Additional themed model packs |

---

## Roadmap

| Feature | Status |
|---------|--------|
| Multi-material painting | ✅ Complete |
| Layer system | ✅ Complete |
| Blockbench import/export | ✅ Complete |
| glTF/GLB import/export | ✅ Complete |
| FBX/OBJ import/export | ✅ Complete |
| Kitbashing | 📋 Planned |
| Diorama / Level Editor | 📋 Planned |
| In-Level Painting | 📋 Planned |

---

## Technical Highlights

- **Engine:** Unity 6.2 with Universal Render Pipeline (URP)
- **Rendering:** Matcap + cavity shading for stylized model preview
- **Input:** Unified touch/mouse/pen system with gesture recognition
- **Storage:** Efficient per-layer PNG persistence with orphan cleanup

---

## Copyright & License

**© 2024-2026 Keith Fox. All Rights Reserved.**

Draw on a Block is proprietary software. This repository is provided for reference and copyright documentation purposes only.

- The source code, assets, and design documents in this repository are **not open source**.
- Redistribution, modification, or commercial use of any materials is **strictly prohibited** without explicit written permission.
- All exported content created by users within the application belongs to those users and may be used freely in personal and commercial projects.

### Establishing Priority

This repository serves as a dated public record of the Draw on a Block project, its features, architecture, and implementation. The commit history documents the development timeline and establishes authorship.

**First public commit:** January 2026  
**Initial concept date:** 2024  
**Author:** Keith Fox

---

## Contact

- **Support:** [To Be Added Later]
- **Business Inquiries:** [To Be Added Later]
- **Website:** [To Be Added Later]

---

## Acknowledgments

- [Endesga](https://lospec.com/palette-list/endesga-32) for the beautiful color palettes
- The Unity and Github communities for invaluable resources and support
- Our beta testers for their feedback and working for friendship points

---

*Draw on a Block — Is it a toy or a tool?*
