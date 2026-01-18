# Draw on a Block — User Guide

Welcome to **Draw on a Block**, a pixel painting app for 3D models! Paint directly on blocks, creatures, furniture, and more with intuitive tools designed for both PC and mobile.

---

## Table of Contents

1. [Getting Started](#getting-started)
2. [Common Interface Elements](#common-interface-elements)
3. [Project View](#project-view)
4. [Adding Models](#adding-models)
5. [Model Painter](#model-painter)
   - [Interface Overview](#interface-overview)
   - [Camera Controls](#camera-controls)
   - [Painting Tools](#painting-tools)
   - [Layers](#layers)
   - [Palettes](#palettes)
   - [Selections](#selections)
6. [Exporting Your Work](#exporting-your-work)
7. [Decal Library](#decal-library)
8. [Palette Manager](#palette-manager)
9. [Store & Pro Unlock](#store--pro-unlock)
10. [Settings](#settings)
11. [Keyboard Shortcuts (PC)](#keyboard-shortcuts-pc)
12. [Troubleshooting & FAQ](#troubleshooting--faq)

---

## Getting Started

When you first launch Draw on a Block, you'll see the **Project View** — your workspace for managing models.

### First Steps

1. Tap ![Add](icons/icon_6_5.png) **Add Model** to open the Model Catalog
2. Browse categories and select a model (many free models are available in each category!)
3. Choose a texture resolution (higher = more detail, larger file size)
4. Your model appears in the project — tap it to start painting

### Quick Tips

- **Auto-save**: Your work is saved automatically as you paint and make changes
- **Undo mistakes**: Use the ![Undo](icons/icon_2_6.png) undo button or `Ctrl+Z` (PC) to reverse changes
- **Get help**: Tap ![Help](icons/icon_6_6.png) in the Model Painter to enter Help Mode — then tap any icon to learn what it does

---

## Common Interface Elements

Many screens in Draw on a Block share similar layouts. Understanding these patterns will help you navigate the app quickly.

### Tile Grids

Throughout the app, you'll encounter grids of tiles for selecting models, palettes, decals, and more:

- **Tap** a tile to select it
- **Double-tap** (PC) or **single tap** (mobile) to open/activate the item
- **Long-press** (mobile) to enter multi-select mode
- Tiles display a **thumbnail** and **name label**

### Header Bars

Most screens have a header bar with:

- ![Menu](icons/icon_6_1.png) **Menu** (top-left): Access navigation and settings
- **Title** (center): Current screen or project name
- **Action buttons** (top-right): Context-specific actions

### Popups and Overlays

Full-screen overlays (like Settings or Add Model) can be closed by:

- Tapping the ![Close](icons/icon_8_2.png) close button
- Tapping the ![Back](icons/icon_7_1.png) back button
- Pressing **Escape** (PC)

---

## Project View

The Project View is your home base for managing all models in your current project.

### What You Can Do

| Action | How |
|--------|-----|
| Open a model | Double-click (PC) or tap (mobile) |
| Select models | Click (PC) or long-press (mobile) |
| Add a model | Tap the ![Add](icons/icon_6_5.png) tile |
| Rename a model | Select it, then tap ![Rename](icons/icon_2_3.png) |
| Delete models | Select and tap ![Delete](icons/icon_6_3.png) |
| Duplicate models | Select and tap ![Duplicate](icons/icon_7_4.png) |
| Reorder models | Drag tiles to new positions |
| Export models | Select and tap ![Export](icons/icon_4_1.png) |

### Menu Options

Tap ![Menu](icons/icon_6_1.png) to access:

- **Project Manager** — Create, open, or manage projects
- **Store** — Browse and purchase model packs
- **Decal Library** — View available decals
- **Edit Palettes** — Manage color palettes
- **Open Project Folder** — (PC only) Open textures folder in File Explorer
- **Settings** — App preferences and controls
- **User Guide** — Opens this guide
- **Report Bug** — Send feedback to developers
- **Close Draw on a Block** — Exit the app

---

## Adding Models

The **Add Model** screen lets you browse and add models to your project.

### Using the Model Catalog

1. Open the catalog via ![Add](icons/icon_6_5.png) in Project View
2. Browse categories using the tabs (Blocks, Creatures, Furniture, etc.)
3. Each category contains free starter models — look for unlocked items
4. Tap a model to see details
5. Choose your **texture resolution**:
   - Lower (16×16, 32×32): Retro pixel art style
   - Medium (64×64, 128×128): Balanced detail
   - Higher (256×256+): Fine details, larger files
6. Tap **Add to Project** to confirm

### Importing Custom Models (Pro Feature)

With **Pro Unlock**, you can import your own 3D models:

**Supported formats**: FBX, OBJ, GLTF, GLB, BBModel (Blockbench)

1. Tap **Import Model** in the Add Model screen
2. Select your model file
3. Configure materials and texture resolutions
4. Tap **Import** to add to your project

---

## Model Painter

The Model Painter is where you create your pixel art directly on 3D models.

### Interface Overview

#### PC Layout

```
┌─────────────────────────────────────────────────────────────┐
│ [Home][Undo][Redo] | [Tools...] | [Zoom][Rot] | [View] | [?]│  ← Top Bar
├─────────────────────────────────────────────────────────────┤
│                                                         │ P │
│                     3D Viewport                         │ A │  ← Palette
│                    (Your Model)                         │ L │     Panel
│                                                         │   │
├─────────────────────────────────────────────────────────────┤
│ [Brush Size] [Tool Options...] [Color]                      │  ← Context Bar
└─────────────────────────────────────────────────────────────┘
```

#### Mobile Layout

- **Top bar**: Home, layers, and view toggles
- **Bottom bar**: Current tool options
- **Side palette**: Quick color selection
- **Floating buttons**: Undo/redo access

### Camera Controls

Navigate around your model to paint from any angle:

| Platform | Rotate | Zoom | Pan |
|----------|--------|------|-----|
| **PC** | Left-click + drag | Scroll wheel | Middle-click + drag |
| **Mobile** | One finger drag | Pinch | Two finger drag |

#### View Options

- ![Grid](icons/icon_4_6.png) **Grid**: Toggle texel grid overlay to see pixel boundaries
- ![Explode](icons/icon_6_2.png) **Explode**: Separate model parts for easier painting (if supported)
- ![Rotation Snap](icons/icon_6_7.png) **Rotation Snap**: Snap camera rotation to 45° increments

---

### Painting Tools

Draw on a Block provides a variety of tools for creating pixel art. Select tools from the toolbar, then paint by clicking/tapping on the model.

#### Basic Tools

| Tool | Icon | Description |
|------|------|-------------|
| **Selection** | ![Selection](icons/icon_1_1.png) | Select rectangular regions for copy/paste/transform |
| **Brush** | ![Brush](icons/icon_1_3.png) | Paint pixels with the current color |
| **Eraser** | ![Eraser](icons/icon_1_4.png) | Remove pixels (make transparent) |
| **Fill** | ![Fill](icons/icon_4_4.png) | Fill a face or selection with color |
| **Color Picker** | ![Color Picker](icons/icon_8_4.png) | Sample a color from the model |

> **Tip (PC)**: Hold **Alt** to temporarily switch to the Color Picker while using any tool.

#### Shape Tools

| Tool | Icon | Description |
|------|------|-------------|
| **Line** | ![Line](icons/icon_5_3.png) | Draw straight lines between two points |
| **Rectangle (Hollow)** | ![Rect Hollow](icons/icon_1_5.png) | Draw rectangular outlines |
| **Rectangle (Solid)** | ![Rect Solid](icons/icon_2_5.png) | Draw filled rectangles |
| **Circle (Hollow)** | ![Circle Hollow](icons/icon_3_5.png) | Draw circular outlines |
| **Circle (Solid)** | ![Circle Solid](icons/icon_4_5.png) | Draw filled circles |

#### Advanced Tools

| Tool | Icon | Description |
|------|------|-------------|
| **Spray Paint** | ![Spray](icons/icon_4_3.png) | Paint with randomized dot patterns |
| **Blend Brush** | ![Blend Brush](icons/icon_10_2.png) | Smooth colors by blending neighboring pixels |
| **Blend Line** | ![Blend Line](icons/icon_11_2.png) | Create smooth color transitions along a line |
| **Linear Gradient** | ![Linear Gradient](icons/icon_12_1.png) | Fill with a gradient between two points |
| **Radial Gradient** | ![Radial Gradient](icons/icon_13_1.png) | Fill with a circular gradient from center outward |
| **Replace Color** | ![Replace Color](icons/icon_11_1.png) | Replace all instances of one color with another on a face |
| **Face Eraser** | ![Face Eraser](icons/icon_2_4.png) | Erase an entire face at once |
| **Stamp** | ![Stamp](icons/icon_5_5.png) | Apply decals from your decal library |

#### Tool Options

Most tools have adjustable settings in the **Context Bar**:

- **Brush Size**: 1-16 pixels (use slider or +/- buttons)
- **Gradient Colors**: Two color boxes for gradient tools

---

### Layers

Layers let you organize your painting into separate, editable surfaces — just like in Photoshop or other image editors.

#### Why Use Layers?

- Paint details on separate layers without affecting base colors
- Toggle visibility to compare variations
- Merge layers when satisfied with the result

#### Layer Controls

Open the **Layer Window** by tapping ![Layers](icons/icon_6_5.png) or pressing **L** (PC).

| Action | How |
|--------|-----|
| Add layer | Tap ![Add](icons/icon_4_8.png) |
| Delete layer | Select layer, tap ![Delete](icons/icon_6_3.png) |
| Toggle visibility | Tap the ![Visibility](icons/icon_6_4.png) icon |
| Rename layer | Double-tap the layer name or tap ![Rename](icons/icon_2_3.png) |
| Reorder layers | Use ![Move Up](icons/icon_13_6.png) / ![Move Down](icons/icon_14_6.png) buttons |
| Merge down | Select layer, tap ![Merge](icons/icon_12_6.png) |
| Duplicate layer | Select layer, tap ![Duplicate](icons/icon_7_4.png) |

> **Note**: Each model supports up to **16 layers**. The bottom layer is the base; layers above are composited on top.

---

### Palettes

Palettes are collections of colors for quick access while painting.

#### Quick Palette (Model Painter)

The **Palette Panel** on the right side of the screen shows your active palette:

- Tap any color to select it as your brush color
- The selected color is highlighted with a border

#### Switching Palettes

1. Tap the ![Edit Palette](icons/icon_3_8.png) **Edit Palette** button to open the Palette Manager
2. Select a different palette from the list on the left
3. Close the Palette Manager — the new palette is now active

> For creating and editing palettes, see [Palette Manager](#palette-manager).

---

### Selections

Selections allow you to work on specific regions of your texture.

#### Making a Selection

1. Choose the **Selection Tool** (![Selection](icons/icon_1_1.png))
2. Click and drag on a face to define a rectangular region
3. A marching-ants border shows the selected area

#### Selection Actions

With an active selection, you can:

| Action | Shortcut (PC) | Icon | Description |
|--------|---------------|------|-------------|
| Copy | `Ctrl+C` | ![Copy](icons/icon_2_1.png) | Copy selected pixels to clipboard |
| Cut | `Ctrl+X` | | Cut selected pixels (copies then deletes) |
| Paste | `Ctrl+V` | ![Paste](icons/icon_3_1.png) | Paste clipboard contents |
| Delete | `Delete` | | Clear selected pixels |
| Flip Horizontal | `Shift+H` | ![Flip H](icons/icon_2_2.png) | Mirror selection horizontally |
| Flip Vertical | `Shift+V` | ![Flip V](icons/icon_3_2.png) | Mirror selection vertically |
| Rotate CW | `Shift+W` | ![Rotate CW](icons/icon_4_2.png) | Rotate 90° clockwise |
| Rotate CCW | `Shift+Q` | ![Rotate CCW](icons/icon_5_2.png) | Rotate 90° counter-clockwise |
| Move | Arrow keys | | Nudge selection (Shift = 8px) |

#### Deselecting

- Click outside the selection
- Press **Escape**
- Tap the ![Cancel](icons/icon_8_8.png) cancel button

---

## Exporting Your Work

Share your painted models by exporting them as images or 3D files.

### Export Options

1. Select model(s) in Project View
2. Tap ![Export](icons/icon_4_1.png) **Export**
3. Choose export type:

#### Texture Export (PNG)

Export just the painted textures:

- **Merged**: All layers flattened into one image
- **Per-Layer**: Separate PNG for each layer

#### Model Export

Export the full 3D model with textures:

| Format | Best For |
|--------|----------|
| **GLTF/GLB** | Web, game engines, universal compatibility |
| **OBJ** | Most 3D software |
| **FBX** | Game engines (Unity, Unreal) |
| **BBModel** | Blockbench (preserves layers!) |

### Export Settings

- **ZIP Archive**: Bundle all files into a single ZIP
- **Loose Files**: Export to a folder
- **Overwrite/Rename**: Handle existing files

---

## Decal Library

Decals are pre-made images you can stamp onto your models — perfect for eyes, faces, patterns, and details.

### Using Decals

1. Select the **Stamp Tool** (![Stamp](icons/icon_5_5.png))
2. The Decal Library opens (on PC) or select "Load from Library" (on mobile)
3. Browse and tap a decal, then tap **Copy to Clipboard**
4. A toast appears: "Click Face to Paste To"
5. Click/tap on a face to place the decal

### Browsing Decals

Access the Decal Library from:
- **Stamp Tool** in Model Painter
- **Menu > Decal Library** in Project View (browse-only mode)

---

## Palette Manager

The Palette Manager is a full-featured color palette editor.

### Accessing the Palette Manager

- From **Project View**: Menu > **Edit Palettes**
- From **Model Painter**: Tap the ![Edit Palette](icons/icon_3_8.png) **Edit Palette** button

### Managing Palettes

| Action | How |
|--------|-----|
| Create palette | Tap ![Add](icons/icon_6_5.png) **New** |
| Duplicate palette | Select palette, tap ![Duplicate](icons/icon_7_4.png) |
| Delete palette | Select palette, tap ![Delete](icons/icon_6_3.png) |
| Rename palette | Edit the name field at the top |
| Import palette | Tap ![Import](icons/icon_5_1.png) **Import** |

### Editing Colors

With a palette selected:

1. Tap a color swatch to edit it
2. Use the **HSV picker** or **RGB sliders** to adjust
3. Enter a **hex code** for precise colors
4. Tap ![Add](icons/icon_6_5.png) to add new colors
5. Drag colors to reorder them

### Importing Palettes

Supported formats:
- **PNG** — Colors sampled from image
- **JASC PAL** — Paint Shop Pro format
- **ASE** — Adobe Swatch Exchange
- **GPL** — GIMP Palette
- **HEX** — Plain text hex codes (one per line)

---

## Store & Pro Unlock

The Store offers additional model packs and the **Pro Unlock** feature.

### Model Packs

- Browse themed collections (Furniture, Creatures, Vehicles, etc.)
- Each pack contains multiple models
- Purchase unlocks all models in the pack permanently

### Pro Unlock — $29

A one-time purchase that enables:

- ✅ **Import custom 3D models** (FBX, OBJ, GLTF, GLB, BBModel)
- ✅ **Import textures** with your models
- ✅ **Upscale/downscale** imported texture resolutions

### Restoring Purchases

If you reinstall or switch devices:

1. Open **Menu > Store**
2. Scroll to the bottom
3. Tap **Restore Purchases**

---

## Settings

Customize Draw on a Block to fit your workflow.

### Display Settings

| Setting | Description |
|---------|-------------|
| **Cavity Shading** | Edge highlighting effect strength |
| **Matcap Intensity** | Lighting style intensity |
| **Rim Shadow** | Edge darkening effect |
| **Grid Colors** | Customize texel grid overlay colors |
| **Checkerboard** | Transparency indicator colors |

### Control Settings

| Setting | Description |
|---------|-------------|
| **Rotation Sensitivity** | Camera orbit speed |
| **Zoom Sensitivity** | Scroll/pinch zoom speed |
| **Pan Sensitivity** | Camera pan speed |
| **Double-Click Threshold** | Time window for double-click detection |
| **Long-Press Duration** | Hold time to trigger selection mode |

### Presets

- **UV Resolutions**: Customize available resolution options

### Hotkeys (PC Only)

Customize keyboard shortcuts for all tools and actions. See [Keyboard Shortcuts](#keyboard-shortcuts-pc) for defaults.

---

## Keyboard Shortcuts (PC)

All shortcuts can be customized in **Settings > Hotkeys**.

### General

| Action | Default |
|--------|---------|
| Undo | `Ctrl+Z` |
| Redo | `Ctrl+Y` or `Ctrl+Shift+Z` |
| Copy | `Ctrl+C` |
| Cut | `Ctrl+X` |
| Paste | `Ctrl+V` |
| Delete Selection | `Delete` |
| Cancel / Go Back | `Escape` |
| Approve / Commit | `Enter` |
| Zoom In | `Ctrl++` |
| Zoom Out | `Ctrl+-` |
| Toggle Grid | `G` |
| Toggle Explode | `E` |
| Toggle Rotation Snap | `S` |
| Open Layer Window | `L` |
| Help Mode | `F1` |
| Switch Model | `Tab` |
| Color Picker (Hold) | `Alt` *(not customizable)* |

### Paint Tools

| Tool | Default |
|------|---------|
| Selection | `Ctrl+S` |
| Brush | `Ctrl+P` |
| Spray Paint | `Ctrl+A` |
| Line | `Ctrl+L` |
| Eraser | `Ctrl+E` |
| Scrub Brush | `Ctrl+Shift+E` |
| Fill | `Ctrl+F` |
| Replace Color | `Ctrl+Shift+F` |
| Linear Gradient | `Ctrl+G` |
| Radial Gradient | `Ctrl+Shift+G` |
| Blend Brush | `Ctrl+B` |
| Blend Line | `Ctrl+Shift+B` |
| Stamp (Decals) | `Ctrl+D` |
| Rectangle (Hollow) | `Ctrl+R` |
| Rectangle (Solid) | `Ctrl+Shift+R` |
| Circle (Hollow) | `Ctrl+O` |
| Circle (Solid) | `Ctrl+Shift+O` |

### Selection Transforms

| Action | Default |
|--------|---------|
| Flip Horizontal | `Shift+H` |
| Flip Vertical | `Shift+V` |
| Rotate CCW (90°) | `Shift+Q` |
| Rotate CW (90°) | `Shift+W` |
| Move Up (1px) | `↑` |
| Move Down (1px) | `↓` |
| Move Left (1px) | `←` |
| Move Right (1px) | `→` |
| Move Up (8px) | `Shift+↑` |
| Move Down (8px) | `Shift+↓` |
| Move Left (8px) | `Shift+←` |
| Move Right (8px) | `Shift+→` |

---

## Troubleshooting & FAQ

### Common Issues

**Q: My painted changes disappeared!**  
A: Check that you're painting on the correct layer. Hidden layers won't show your work. Your work is auto-saved periodically. If you return to the Project View, your model's texture changes are saved automatically.

**Q: I can't paint on certain faces.**  
A: Check the following:
- Is the layer visible? Hidden layers can't be painted on.
- Do you have an active selection? Painting is confined to the selected area.
- Is the face part of the model's texture? Some decorative elements may not be paintable.

**Q: Colors look different when exported.**  
A: This is usually due to color space differences. Try exporting as PNG with the "sRGB" option if available in your target software.

**Q: Import isn't working (Pro feature).**  
A: Ensure your model file:
- Is a supported format (FBX, OBJ, GLTF, GLB, BBModel)
- Has valid UV mapping
- Isn't corrupted or password-protected

### Getting Help

- **In-App Help**: Tap ![Help](icons/icon_6_6.png) in the Model Painter
- **Report Bugs**: Menu > **Report Bug** ![Bug](icons/icon_12_8.png)
### Contact

For additional support, visit our GitHub repository or community forums.

---

*Thank you for using Draw on a Block! Happy painting! 🎨*
