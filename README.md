# Yard & Property Planner

A browser-based tool for planning and visualizing your property layout with an intuitive drag-and-drop interface.

## Features

- **Property Boundary Definition** - Define your lot using rectangular dimensions, polygon coordinates, or click-to-plot
- **Dot-Matrix Grid** - Beautiful dot-paper aesthetic with adjustable scale (1/2/5/10 ft per dot)
- **Object Library** - Pre-built objects including structures, gardens, landscape features, hardscape, recreation, and utilities
- **Custom Objects** - Create your own objects with custom colors, shapes, and sizes
- **Full Editing** - Move, resize, rotate (15° snaps), duplicate, and delete objects
- **Measurement Tools** - Click two points to measure distances in feet
- **Layers Panel** - Toggle visibility by category
- **Save/Load/Export** - JSON save/load + PNG export + auto-save to localStorage
- **Undo/Redo** - Full undo/redo support (Ctrl+Z / Ctrl+Shift+Z)

## Usage

Simply open `yard-planner.html` in your browser - no installation or server required!

### Keyboard Shortcuts

- **Delete**: Delete selected object
- **Ctrl+D**: Duplicate selected object
- **Ctrl+Z**: Undo
- **Ctrl+Shift+Z**: Redo
- **Shift+Drag**: Pan the canvas
- **Scroll Wheel**: Zoom in/out

### Getting Started

1. Define your property boundary
2. Drag objects from the sidebar onto your property
3. Move, resize, and rotate objects as needed
4. Use the measure tool to check distances
5. Save your work or export as PNG

## Technical Details

- Single HTML file (< 2000 lines)
- Built with [Fabric.js](http://fabricjs.com/)
- Works offline after first load
- No dependencies beyond CDN-loaded Fabric.js

## Default Property

The default rectangular boundary is set to **510 ft × 230 ft** - adjust as needed for your property.

## License

Free to use for personal projects.
