# Draw on a Block — User Guide

Welcome to **Draw on a Block**, a pixel painting app for 3D models! Paint directly on blocks, creatures, furniture, and more with intuitive tools designed for PC.

---

## Table of Contents

1. [Getting Started](#getting-started)
2. [Common Interface Elements](#common-interface-elements)
3. [Models Tab](#models-tab)
4. [Adding Models](#adding-models)
5. [Model Painter](#model-painter)
   - [Interface Overview](#interface-overview)
   - [Camera Controls](#camera-controls)
   - [Painting Tools](#painting-tools)
   - [Layers](#layers)
   - [Palettes](#palettes)
   - [Selections](#selections)
6. [Scenes Tab](#scenes-tab)
7. [Scene Builder](#scene-builder)
8. [Scene Painter](#scene-painter)
9. [Exporting Your Work](#exporting-your-work)
10. [Snapshot & Share](#snapshot--share)
11. [Decal Library](#decal-library)
12. [Palette Manager](#palette-manager)
13. [Settings](#settings)
14. [Keyboard Shortcuts (PC)](#keyboard-shortcuts-pc)
15. [Troubleshooting & FAQ](#troubleshooting--faq)

---

## Getting Started

When you first launch Draw on a Block, you'll see the **Models** tab — your workspace for managing models.

### First Steps

1. Tap <img src="icons/icon_6_5.png" alt="Add" height="20"> **Add Model** to open the Model Catalog
2. Scroll through the catalog and select a model — you can expand/collapse categories as needed
3. Choose a texture resolution (higher = more detail, larger file size)
4. Your model appears in the project — tap it to start painting

### Quick Tips

- **Auto-save**: Your work is saved automatically as you paint and make changes
- **Undo mistakes**: Use the <img src="icons/icon_2_6.png" alt="Undo" height="20"> undo button or `Ctrl + Z` to reverse changes
- **Get help**: Tap <img src="icons/icon_6_6.png" alt="Help" height="20"> in the Model Painter to enter Help Mode — then tap any icon to learn what it does

---

## Common Interface Elements

Many screens in Draw on a Block share similar layouts. Understanding these patterns will help you navigate the app quickly.

### Tile Grids

Throughout the app, you'll encounter grids of tiles for selecting models, palettes, decals, and more:

- **Click** a tile to select it
- **Double-click** to open/activate the item
- **Hover** over a tile to reveal a <img src="icons/icon_6_1.png" alt="Menu" height="20"> menu button in the top-right corner
- Tiles display a **thumbnail** and **name label**

#### Tile Hover Menu

Clicking the <img src="icons/icon_6_1.png" alt="Menu" height="20"> button on a tile reveals a dropdown menu with quick actions:

- <img src="icons/icon_2_3.png" alt="Rename" height="20"> **Rename** — Change the item's name
- <img src="icons/icon_4_2.png" alt="Refresh Textures" height="20"> **Refresh Textures** — Reload textures from disk after external editing
- <img src="icons/icon_10_3.png" alt="Change Resolution" height="20"> **Change Resolution** — Adjust the texture resolution
- <img src="icons/icon_4_1.png" alt="Export" height="20"> **Export** — Export the item
- <img src="icons/icon_7_4.png" alt="Duplicate" height="20"> **Duplicate** — Create a copy
- <img src="icons/icon_6_3.png" alt="Delete" height="20"> **Delete** — Remove the item

### Header Bars

Most screens have a header bar with:

- <img src="icons/icon_6_1.png" alt="Menu" height="20"> **Menu** (top-left): Access navigation and settings
- **Title** (center): Current screen or project name
- **Action buttons** (top-right): Context-specific actions

### Popups and Overlays

Full-screen overlays (like Settings or Add Model) can be closed by:

- Tapping the <img src="icons/icon_7_1.png" alt="Back" height="20"> back button
- Pressing **Escape**

---

## Models Tab

The **Models** tab is your home base for managing all models in your current project. You can switch between the **Models** and **Scenes** tabs using the tab bar at the top.

### What You Can Do

| Action | How |
|--------|-----|
| Open a model | Double-click the model tile |
| Select models | Click a model tile |
| Add a model | Tap the <img src="icons/icon_6_5.png" alt="Add" height="20"> tile |
| Rename a model | Select it, then tap <img src="icons/icon_2_3.png" alt="Rename" height="20"> in the selection menu |
| Delete models | Select and tap <img src="icons/icon_6_3.png" alt="Delete" height="20"> in the selection menu |
| Duplicate models | Select and tap <img src="icons/icon_7_4.png" alt="Duplicate" height="20"> in the selection menu |
| Reorder models | Drag tiles to new positions |
| Export models | Select and tap <img src="icons/icon_4_1.png" alt="Export" height="20"> in the selection menu |
| Toggle view | Tap the view toggle button (top-right) to switch between grid and list view |

### Menu Options

Tap <img src="icons/icon_6_1.png" alt="Menu" height="20"> to access:

- **Project Manager** — Create, open, or manage projects
- **Decal Library** — View available decals
- **Edit Palettes** — Manage color palettes
- **Open Project Folder** — Open textures folder in File Explorer
- **Settings** — App preferences and controls
- **User Guide** — Opens this guide
- **Report Bug** — Send feedback to developers
- **Close Draw on a Block** — Exit the app

---

## Adding Models

The **Add Model** screen lets you browse and add models to your project.

### Using the Model Catalog

1. Open the catalog via <img src="icons/icon_6_5.png" alt="Add" height="20"> in the Models tab
2. Scroll through the catalog to browse models — tap category headers to expand or collapse them
3. Tap a model to see details
4. Choose your **texture resolution** (64×64 to 1024×1024 by default — you can customize available resolutions in Settings)
5. Tap **Add to Project** to confirm

### Importing Custom Models

You can import your own 3D models.

**Supported formats**: FBX, OBJ, GLTF, GLB, BBModel (Blockbench)

#### Import Workflow

1. Tap **Import Model** in the Add Model screen
2. Select your model file from the file picker (if importing a bbmodel, you will be prompted to either merge layers or preserve layers)
3. The import screen appears with the following options:
   - **Import Textures** toggle — Enable to import textures from the model file (if available)
   - **UV Resolution** dropdown — Choose the texture resolution for each material
   - **Translucent/Opaque** toggle — Set whether materials support transparency
4. If the model has multiple materials, they appear in a list where you can configure each one individually
5. Tap **Finalize Import** to add the model to your project

> **Tip**: Ensure your model file's textures are located in the same folder as the model, or the textures may not import correctly.

#### Custom Models in the Model Catalog

Your imported models appear at the top of the Model Catalog. Hover over a custom model tile to access the tile menu with these options:

- <img src="icons/icon_2_3.png" alt="Rename" height="20"> **Rename** — Change the model's display name
- <img src="icons/icon_1_6.png" alt="Configure Materials" height="20"> **Configure Materials** — Adjust settings for each material:
  - **UV Resolution** — Change the texture resolution
  - **Translucent/Opaque** — Toggle transparency support
- <img src="icons/icon_6_3.png" alt="Delete" height="20"> **Delete** — Permanently remove the source model

> **⚠ Warning**: Deleting a custom model from the catalog permanently removes it AND deletes every instance of that model from ALL of your projects — not just the current one. The app will show you how many models will be affected before confirming. Make sure to export anything you want to keep before deleting.

---

## Model Painter

The Model Painter is where you create your pixel art directly on 3D models.

### Interface Overview

#### PC Layout

The PC interface has three main areas:

- **Top Bar**: Contains the Home button (return to Models tab), Undo/Redo buttons, tool selection buttons, view toggles (Grid, Explode, Rotation Snap), and the Help button
- **3D Viewport**: The main area where your model is displayed — this is where you paint
- **Palette Panel**: Displayed on the right side, shows your current color palette for quick color selection
- **Context Bar**: At the bottom of the screen, shows options specific to the currently selected tool (brush size, gradient colors, etc.)

### Camera Controls

Navigate around your model to paint from any angle:

| Action | Control |
|--------|---------|
| **Rotate** | Left-click + drag |
| **Zoom** | Scroll wheel |
| **Pan** | Middle-click + drag |

#### View Options

- <img src="icons/icon_4_6.png" alt="Grid" height="20"> **Grid**: Toggle texel grid overlay to see pixel boundaries
- <img src="icons/icon_6_2.png" alt="Explode" height="20"> **Explode**: Separate model parts for easier painting (if supported)
- <img src="icons/icon_6_7.png" alt="Rotation Snap" height="20"> **Rotation Snap**: Snap camera rotation to 45° increments
- <img src="icons/icon_14_7.png" alt="Focus Mode" height="20"> **Focus Mode** (`Ctrl + H`): Isolate a single face for distraction-free painting. Click the button to arm it, then click any face to zoom in and hide the rest of the model. Click again to exit.

---

### Painting Tools

Draw on a Block provides a variety of tools for creating pixel art. Select tools from the toolbar, then paint by clicking on the model.

#### Basic Tools

| Tool | Icon | Description |
|------|------|-------------|
| **Selection** | <img src="icons/icon_1_1.png" alt="Selection" height="20"> | Select rectangular regions for copy/paste/transform |
| **Brush** | <img src="icons/icon_1_3.png" alt="Brush" height="20"> | Paint pixels with the current color |
| **Eraser** | <img src="icons/icon_1_4.png" alt="Eraser" height="20"> | Remove pixels (make transparent) |
| **Fill** | <img src="icons/icon_4_4.png" alt="Fill" height="20"> | Fill a face or selection with color |
| **Color Picker** | <img src="icons/icon_8_4.png" alt="Color Picker" height="20"> | Sample a color from the model |

> **Tip**: Hold **Alt** to temporarily switch to the Color Picker while using any tool.

#### Shape Tools

| Tool | Icon | Description |
|------|------|-------------|
| **Line** | <img src="icons/icon_5_3.png" alt="Line" height="20"> | Draw straight lines between two points |
| **Rectangle (Hollow)** | <img src="icons/icon_1_5.png" alt="Rect Hollow" height="20"> | Draw rectangular outlines |
| **Rectangle (Solid)** | <img src="icons/icon_2_5.png" alt="Rect Solid" height="20"> | Draw filled rectangles |
| **Circle (Hollow)** | <img src="icons/icon_3_5.png" alt="Circle Hollow" height="20"> | Draw circular outlines |
| **Circle (Solid)** | <img src="icons/icon_4_5.png" alt="Circle Solid" height="20"> | Draw filled circles |

#### Advanced Tools

| Tool | Icon | Description |
|------|------|-------------|
| **Spray Paint** | <img src="icons/icon_4_3.png" alt="Spray" height="20"> | Paint with randomized dot patterns |
| **Blend Brush** | <img src="icons/icon_10_2.png" alt="Blend Brush" height="20"> | Smooth colors by blending neighboring pixels |
| **Blend Line** | <img src="icons/icon_11_2.png" alt="Blend Line" height="20"> | Create smooth color transitions along a line |
| **Linear Gradient** | <img src="icons/icon_12_1.png" alt="Linear Gradient" height="20"> | Fill with a gradient between two points |
| **Radial Gradient** | <img src="icons/icon_13_1.png" alt="Radial Gradient" height="20"> | Fill with a circular gradient from center outward |
| **Replace Color** | <img src="icons/icon_11_1.png" alt="Replace Color" height="20"> | Replace all instances of one color with another on a face |
| **Face Eraser** | <img src="icons/icon_2_4.png" alt="Face Eraser" height="20"> | Erase an entire face at once |
| **Stamp** | <img src="icons/icon_5_5.png" alt="Stamp" height="20"> | Apply decals from your decal library |

#### Tool Options

Most tools have adjustable settings in the **Context Bar**:

- **Brush Size**: 1-100 pixels. The slider uses a quadratic curve for finer control at small sizes. Click the value label to type an exact number.
- **Blend Power**: 1-100% strength for blend tools
- **Include Transparent** (Blend tools): Toggle to include transparent pixels in blend calculations without color contamination
- **Gradient Colors**: Two color boxes used by the gradient tools. Click a color box to assign it the currently selected palette color. Then choose a different color from the palette and click the other color box. The gradient will blend between these two colors.

> **Tip**: Click on any slider's numeric value to type an exact number directly.

---

### Layers

Layers let you organize your painting into separate, editable surfaces — just like in Photoshop or other image editors.

#### Why Use Layers?

- Paint details on separate layers without affecting base colors
- Toggle visibility to compare variations
- Use blend modes to create lighting and shadow effects
- Merge layers when satisfied with the result

#### Layer Controls

Open the **Layer Window** by tapping <img src="icons/icon_6_5.png" alt="Layers" height="20"> or pressing **L**.

| Action | How |
|--------|-----|
| Add layer | Tap <img src="icons/icon_4_8.png" alt="Add" height="20"> in the layer toolbar |
| Delete layer | Select layer, tap <img src="icons/icon_6_3.png" alt="Delete" height="20"> in the layer toolbar |
| Toggle visibility | Tap the <img src="icons/icon_6_4.png" alt="Visibility" height="20"> icon on the layer row |
| Rename layer | Double-tap the layer name or tap <img src="icons/icon_2_3.png" alt="Rename" height="20"> in the layer toolbar |
| Reorder layers | Use <img src="icons/icon_13_6.png" alt="Move Up" height="20"> / <img src="icons/icon_14_6.png" alt="Move Down" height="20"> buttons in the layer toolbar |
| Merge down | Select layer, tap <img src="icons/icon_12_6.png" alt="Merge" height="20"> in the layer toolbar |
| Duplicate layer | Select layer, tap <img src="icons/icon_7_4.png" alt="Duplicate" height="20"> in the layer toolbar |
| Toggle layer options | Tap <img src="icons/icon_15_6.png" alt="Layer Options" height="20"> to reveal blend mode and opacity controls |
| Change blend mode | Use the blend mode dropdown (Normal, Multiply, Screen) |
| Change opacity | Use the opacity slider (drag to adjust 0–100%) |
| View UV image | Tap <img src="icons/icon_9_7.png" alt="View UV" height="20"> to see the flattened UV texture |
| Switch material | If your model has multiple materials, use the material dropdown to switch between them |

> **Note**: The bottom layer is the base; layers above are composited on top. Layer count is limited only by your hardware.

> **Tip**: Undo/redo (`Ctrl+Z` / `Ctrl+Y`) works while the layer popup is open. Undoing a layer operation will automatically open the popup if it's closed, and undoing a paint stroke will close it.

---

### Palettes

Palettes are collections of colors for quick access while painting.

#### Quick Palette (Model Painter)

The **Palette Panel** on the right side of the screen shows your active palette:

- Tap any color to select it as your brush color
- The selected color is highlighted with a border

#### Using the Color Picker

When you use the **Color Picker** tool to sample a color from your model:

- If the color exists in your palette, it becomes selected
- If the color is **not** in your current palette, it appears at the end of the palette with a <img src="icons/icon_6_5.png" alt="Plus" height="20"> overlay
- Tap the plus icon to add the color to your palette
- If you're using a **built-in palette**, adding a color will create a duplicate in your **Custom** palettes that you can freely edit

#### Switching Palettes

1. Tap the <img src="icons/icon_3_8.png" alt="Edit Palette" height="20"> **Edit Palette** button to open the Palette Manager
2. Select a different palette from the list on the left
3. Close the Palette Manager — the new palette is now active

> For creating and editing palettes, see [Palette Manager](#palette-manager).

---

### Selections

Selections allow you to work on specific regions of your texture.

#### Making a Selection

1. Choose the **Selection Tool** (<img src="icons/icon_1_1.png" alt="Selection" height="20">)
2. Click and drag on a face to define a rectangular region
3. A marching-ants border shows the selected area
4. Use the **scale handles** on the corners and edges to resize your selection

#### Magic Wand Selection

Use the <img src="icons/icon_10_5.png" alt="Magic Wand" height="20"> **Magic Wand** to select all contiguous pixels of the same color:

- Magic Wand is a dedicated tool in the main toolbar (below Selection)
- Click on any pixel — all connected pixels of that color will be selected
- The tool stays active for multiple selections
- Use **Shift + Click** to add to the current selection
- Use **Ctrl + Click** to subtract from the current selection

#### Selection Actions

With an active selection, you can use the buttons in the selection context bar:

| Action | Shortcut | Icon | Description |
|--------|----------|------|-------------|
| Magic Wand | `Ctrl + W` | <img src="icons/icon_10_5.png" alt="Magic Wand" height="20"> | Select contiguous area of same color |
| Copy | `Ctrl + C` | <img src="icons/icon_2_1.png" alt="Copy" height="20"> | Copy selected pixels to clipboard |
| Paste | `Ctrl + V` | <img src="icons/icon_3_1.png" alt="Paste" height="20"> | Paste clipboard contents |
| Flip Horizontal | `Shift + H` | <img src="icons/icon_2_2.png" alt="Flip H" height="20"> | Mirror selection horizontally |
| Flip Vertical | `Shift + V` | <img src="icons/icon_3_2.png" alt="Flip V" height="20"> | Mirror selection vertically |
| Rotate CW | `Shift + W` | <img src="icons/icon_4_2.png" alt="Rotate CW" height="20"> | Rotate 90° clockwise |
| Rotate CCW | `Shift + Q` | <img src="icons/icon_5_2.png" alt="Rotate CCW" height="20"> | Rotate 90° counter-clockwise |
| Save to Decals | | <img src="icons/icon_4_1.png" alt="Save" height="20"> | Save selection to Decal Library |
| Move | Arrow keys | | Nudge selection (Shift = 8px) |

#### Deselecting

- Click outside the selection
- Press **Escape**

---

## Scenes Tab

The **Scenes** tab lets you manage scene compositions. Switch to the Scenes tab using the tab bar at the top of the Models tab.

### What You Can Do

| Action | How |
|--------|-----|
| Create a scene | Tap the <img src="icons/icon_6_5.png" alt="Add" height="20"> tile |
| Open a scene | Double-click the scene tile |
| Rename a scene | Select it, then tap <img src="icons/icon_2_3.png" alt="Rename" height="20"> in the selection menu |
| Delete scenes | Select and tap <img src="icons/icon_6_3.png" alt="Delete" height="20"> in the selection menu |
| Duplicate scenes | Select and tap <img src="icons/icon_7_4.png" alt="Duplicate" height="20"> in the selection menu |

> **Note**: Each scene uses models from your project. Adding or removing models in the Models tab updates which models are available for placement in scenes.

---

## Scene Builder

The Scene Builder lets you arrange models from your project into a 3D scene on a grid-based workspace.

### Opening the Scene Builder

1. Go to the **Scenes** tab
2. Double-click a scene tile (or create a new one with <img src="icons/icon_6_5.png" alt="Add" height="20">)
3. The Scene Builder opens with an empty grid (or your previously saved arrangement)

### Builder Toolbar

The top bar provides these controls:

| Button | Icon | Description |
|--------|------|-------------|
| **Home** | <img src="icons/icon_7_1.png" alt="Home" height="20"> | Return to the Scenes tab |
| **Undo** | <img src="icons/icon_2_6.png" alt="Undo" height="20"> | Undo the last action |
| **Redo** | <img src="icons/icon_3_6.png" alt="Redo" height="20"> | Redo the last undone action |
| **Add Model** | <img src="icons/icon_6_5.png" alt="Add" height="20"> | Open the model picker to place a model |
| **Paint Scene** | <img src="icons/icon_1_3.png" alt="Paint" height="20"> | Switch to Scene Painter mode |
| **Grid Toggle** | <img src="icons/icon_4_6.png" alt="Grid" height="20"> | Show/hide the placement grid |
| **Snapshot** | <img src="icons/icon_9_8.png" alt="Snapshot" height="20"> | Capture a snapshot of the scene |
| **Help** | <img src="icons/icon_6_6.png" alt="Help" height="20"> | Enter Help Mode |

### Placing Models

1. Tap <img src="icons/icon_6_5.png" alt="Add" height="20"> **Add Model** in the toolbar
2. Select a model from your project's model list
3. The model appears on the grid at the cursor position
4. Click to place the model

### Transforming Models

Select a placed model to transform it:

| Action | Control | Shortcut |
|--------|---------|----------|
| **Move** | Drag the model | Arrow keys (grid-snapped) |
| **Move (fine)** | Hold **Shift** + drag | Shift + Arrow keys (½ grid step) |
| **Rotate** | Click while placing, or use shortcut | `Space` (90° increments) |
| **Flip** | Mirror the model | `F` |
| **Reset rotation** | Reset to default orientation | `R` |
| **Delete** | Remove the selected model | `Delete` |

> **Tip**: Hold **Shift** while dragging a model to move it in half-grid increments for finer positioning.

### Grid Levels

The Scene Builder uses a layered grid system. You can raise or lower the active grid level to place models at different heights:

| Action | Shortcut |
|--------|----------|
| **Grid Up** | `Shift + W` |
| **Grid Down** | `Shift + S` |

#### Grid Axis

By default, models are placed on the **Y axis** (horizontal floor). You can cycle the placement axis to build on walls or ceilings:

| Axis | Grid Plane | Icon |
|------|-----------|------|
| **Y** (default) | Horizontal floor | <img src="icons/icon_13_5.png" alt="Y Axis" height="20"> |
| **Z** | Vertical wall (front/back) | <img src="icons/icon_14_5.png" alt="Z Axis" height="20"> |
| **X** | Vertical wall (left/right) | <img src="icons/icon_12_5.png" alt="X Axis" height="20"> |

Press **A** to cycle through axes: Y → Z → X → Y.

### Forking Models

**Fork** creates an independent copy of a model's textures, allowing you to paint unique variations without affecting the original:

1. Select a placed model
2. Press `Ctrl + F` or use the Fork button
3. The model now has its own independent texture

> **Tip**: Without forking, all instances of the same model share textures — painting one changes them all. Fork when you want unique appearances.

### Entering Scene Painter

To paint models within your scene:

1. Tap <img src="icons/icon_1_3.png" alt="Paint" height="20"> **Paint Scene** in the toolbar, or press **Tab**
2. The Scene Builder transitions to **Scene Painter** mode
3. Press **Tab** again to return to the Scene Builder

---

## Scene Painter

The Scene Painter lets you paint models directly within a scene, without leaving the scene context.

### Opening the Scene Painter

From the **Scene Builder**, switch to Scene Painter by:

- Tapping <img src="icons/icon_1_3.png" alt="Paint" height="20"> **Paint Scene** in the toolbar
- Pressing **Tab**

### Scene Painter vs. Model Painter

| Feature | Model Painter | Scene Painter |
|---------|--------------|---------------|
| Open from | Models tab | Scene Builder |
| Paints on | Single model | Any model in the scene |
| Camera shows | One model | Entire scene |
| Switch model | N/A | Just paint on any model |
| Grid/Explode | Per-model | Per-model (on selected) |

### Cross-Model Painting

In the Scene Painter, you can paint seamlessly across different models in your scene — simply move your brush to any visible model and start painting. There is no need to manually select or switch models; the painter automatically detects which model you're painting on.

### Forking in Scene Painter

You can fork models directly from Scene Painter using `Ctrl + F`. This creates an independent texture copy for the currently selected model, letting you give it a unique appearance within the scene.

### Returning to Scene Builder

Press **Tab** or tap the <img src="icons/icon_9_5.png" alt="Builder" height="20"> **Scene Builder** button in the toolbar to return to the Scene Builder.

---

## Exporting Your Work

Share your painted models by exporting them as images or 3D files.

### Export Screen

1. Select model(s) in the Models tab
2. Tap <img src="icons/icon_4_1.png" alt="Export" height="20"> **Export** in the selection menu
3. The Export screen appears showing:
   - A list of selected models with their materials and layer counts
   - **Merge Layers** toggle — When on, all layers are flattened into a single texture
   - **Export Models** toggle — When on, exports 3D model files along with textures
   - **Format dropdown** (when Export Models is on) — Choose GLTF, OBJ, or BBModel
   - **Zip Exports** toggle — Bundle output into a ZIP archive

4. Tap **Export** to save your files

> **Note**: If a file with the same name already exists in the destination folder, you'll be prompted to either overwrite or rename.

### Export Formats

| Format | Best For |
|--------|----------|
| **GLTF** | Web, game engines, universal compatibility |
| **OBJ** | Most 3D software |
| **BBModel** | Blockbench (preserves layers!) |

---

## Snapshot & Share

Capture images of your painted models and scenes to share with others.

### Taking a Snapshot

1. Tap <img src="icons/icon_9_8.png" alt="Snapshot" height="20"> **Snapshot** in the Model Painter or Scene Builder toolbar
2. The Snapshot screen appears with a preview and options

### Snapshot Options

| Option | Description |
|--------|-------------|
| **Format** | PNG (transparent background) or JPG (solid background) |
| **Resolution** | Set the output image resolution |
| **Background** | Choose a solid background color (JPG) or transparent (PNG) |
| **Show Grid** | Toggle grid overlay visibility in the snapshot |
| **Animate** | Toggle turntable animation for animated GIF/video export |
| **Camera** | Adjust the camera angle and zoom for the snapshot |
| **Rendering** | Switch between rendering styles |

### Saving & Sharing

- Tap **Save** to save the snapshot to your file system
- Tap **Copy** to copy the image to your clipboard
- Use `Ctrl + PrintScreen` from the Model Painter to quickly copy a 4K screenshot to your clipboard

---

## Decal Library

Decals are pre-made images you can stamp onto your models — perfect for eyes, faces, patterns, and details.

### Using Decals

1. Select the **Stamp Tool** (<img src="icons/icon_5_5.png" alt="Stamp" height="20">)
2. The Decal Library opens
3. Browse and tap a decal, then tap **Copy to Clipboard**
4. A toast appears: "Click Face to Paste To"
5. Click on a face to place the decal

### Managing Decals

| Action | How |
|--------|-----|
| Import decal | Tap <img src="icons/icon_6_5.png" alt="Add" height="20"> to import an image file as a new decal |
| Export decal | Select a decal and tap <img src="icons/icon_4_1.png" alt="Export" height="20"> in the selection menu |
| Delete decal | Select and tap <img src="icons/icon_6_3.png" alt="Delete" height="20"> in the selection menu |

### Browsing Decals

Access the Decal Library from:
- **Stamp Tool** in Model Painter
- **Menu > Decal Library** in the Models tab (browse-only mode)

---

## Palette Manager

The Palette Manager is a full-featured color palette editor.

### Accessing the Palette Manager

- From the **Models tab**: Menu > **Edit Palettes**
- From **Model Painter**: Tap the <img src="icons/icon_3_8.png" alt="Edit Palette" height="20"> **Edit Palette** button

### Palette Tabs

At the bottom of the palette list, you'll find two tabs:

- **Built-in** — Pre-made palettes that come with the app (read-only)
- **Custom** — Your own palettes that you can freely edit

> **Note**: Built-in palettes cannot be modified. If you edit a built-in palette, a copy is automatically created in your Custom tab.

### Managing Palettes

| Action | How |
|--------|-----|
| Create palette | Tap <img src="icons/icon_6_5.png" alt="Add" height="20"> **New** |
| Duplicate palette | Select palette, tap <img src="icons/icon_7_4.png" alt="Duplicate" height="20"> |
| Delete palette | Select palette, tap <img src="icons/icon_6_3.png" alt="Delete" height="20"> (custom palettes only) |
| Rename palette | Edit the name field at the top |
| Import palette | Tap <img src="icons/icon_5_1.png" alt="Import" height="20"> **Import** |

### Editing Colors

With a palette selected:

1. Tap a color swatch to select it
2. Use the **HSV picker** or **RGB sliders** to adjust
3. Enter a **hex code** for precise colors
4. Tap <img src="icons/icon_6_5.png" alt="Add" height="20"> to add new colors
5. Use the **swap left/right** icons to reorder colors (dragging is not supported)

### Importing Palettes

Supported formats:
- **PNG** — Colors sampled from image
- **JASC PAL** — Paint Shop Pro format
- **ASE** — Adobe Swatch Exchange
- **GPL** — GIMP Palette
- **HEX** — Plain text hex codes (one per line)

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
| **Zoom Sensitivity** | Scroll zoom speed |
| **Pan Sensitivity** | Camera pan speed |
| **Double-Click Threshold** | Time window for double-click detection |

### Presets

- **UV Resolutions**: Customize available resolution options

### Hotkeys

Customize keyboard shortcuts for all tools and actions. See [Keyboard Shortcuts](#keyboard-shortcuts-pc) for defaults.

---

## Keyboard Shortcuts (PC)

All shortcuts can be customized in **Settings > Hotkeys**.

### General

| Action | Default |
|--------|---------|
| Undo | `Ctrl + Z` |
| Redo | `Ctrl + Y` or `Ctrl + Shift + Z` |
| Copy | `Ctrl + C` |
| Cut | `Ctrl + X` |
| Paste | `Ctrl + V` |
| Delete Selection | `Delete` |
| Cancel / Go Back | `Escape` |
| Approve / Commit | `Enter` |
| Zoom In | `Ctrl + +` |
| Zoom Out | `Ctrl + -` |
| Toggle Grid | `G` |
| Toggle Explode | `E` |
| Toggle Rotation Snap | `S` |
| Open Layer Window | `L` |
| Focus Mode | `Ctrl + H` |
| Help Mode | `F1` |
| Color Picker (Hold) | `Alt` *(not customizable)* |
| Copy 4K Screenshot | `Ctrl + PrintScreen` |

### Paint Tools

| Tool | Default |
|------|---------|
| Magic Wand | `Ctrl + W` |
| Selection | `Ctrl + S` |
| Brush | `Ctrl + P` |
| Spray Paint | `Ctrl + A` |
| Line | `Ctrl + L` |
| Eraser | `Ctrl + E` |
| Scrub Brush | `Ctrl + Shift + E` |
| Fill | `Ctrl + F` |
| Replace Color | `Ctrl + Shift + F` |
| Linear Gradient | `Ctrl + G` |
| Radial Gradient | `Ctrl + Shift + G` |
| Blend Brush | `Ctrl + B` |
| Blend Line | `Ctrl + Shift + B` |
| Stamp (Decals) | `Ctrl + D` |
| Rectangle (Hollow) | `Ctrl + R` |
| Rectangle (Solid) | `Ctrl + Shift + R` |
| Circle (Hollow) | `Ctrl + O` |
| Circle (Solid) | `Ctrl + Shift + O` |

### Selection Modifiers

| Action | Keys |
|--------|------|
| Add to Selection | `Shift + Click` (drag or Magic Wand) |
| Subtract from Selection | `Alt + Click` (drag or Magic Wand) |

### Selection Transforms

| Action | Default |
|--------|---------|
| Flip Horizontal | `Shift + H` |
| Flip Vertical | `Shift + V` |
| Rotate CCW (90°) | `Shift + Q` |
| Rotate CW (90°) | `Shift + W` |
| Move Up (1px) | `↑` |
| Move Down (1px) | `↓` |
| Move Left (1px) | `←` |
| Move Right (1px) | `→` |
| Move Up (8px) | `Shift + ↑` |
| Move Down (8px) | `Shift + ↓` |
| Move Left (8px) | `Shift + ←` |
| Move Right (8px) | `Shift + →` |

### Scene Builder

| Action | Default |
|--------|---------|
| Switch to Scene Painter | `Tab` |
| Rotate Model | `Space` |
| Flip Model | `F` |
| Reset Rotation | `R` |
| Cycle Grid Axis | `A` |
| Place Single | `S` |
| Paint Area | `P` |
| Grid Up | `Shift + W` |
| Grid Down | `Shift + S` |
| Fork Model | `Ctrl + F` |
| Reset Camera | `H` |

### Scene Painter

| Action | Default |
|--------|---------|
| Switch to Scene Builder | `Tab` |
| Fork Model | `Ctrl + F` |

---

## Troubleshooting & FAQ

### Common Issues

**Q: My painted changes disappeared!**  
A: Check that you're painting on the correct layer. Hidden layers won't show your work. Your work is auto-saved periodically. If you return to the Models tab, your model's texture changes are saved automatically.

**Q: I can't paint on certain faces.**  
A: Check the following:
- Is the layer visible? Hidden layers can't be painted on.
- Do you have an active selection? Painting is confined to the selected area.

**Q: Colors look different when exported.**  
A: This is usually due to color space differences. Try exporting as PNG with the "sRGB" option if available in your target software.

**Q: Import isn't working.**  
A: Ensure your model file:
- Is a supported format (FBX, OBJ, GLTF, GLB, BBModel)
- Has valid UV mapping
- Isn't corrupted or password-protected
- Has its textures in the same folder as the model file (textures must be accessible)

### Getting Help

- **In-App Help**: Tap <img src="icons/icon_6_6.png" alt="Help" height="20"> in the Model Painter
- **Report Bugs**: Menu > **Report Bug** <img src="icons/icon_12_8.png" alt="Bug" height="20">
- **This Guide**: Menu > **User Guide**

### Contact

For additional support, visit our GitHub repository or community forums.

---

*Thank you for using Draw on a Block! Happy painting! 🎨*
