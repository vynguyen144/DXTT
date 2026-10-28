# Lumen Studio — Photo Editor

A browser-based photo editor prototype focused on non-destructive local adjustments.

## Current features
- Import images from your device or drag-and-drop into the workspace.
- Work locally in the browser; the source file is not overwritten or uploaded to a server.
- Separate adjustment layers with independent visibility, opacity, ordering, and masks.
- Brush masks, eraser, linear gradient, radial gradient, rectangular masks, mask inversion, and mask overlay preview.
- Local exposure, brightness, contrast, highlights, shadows, whites, blacks, temperature, tint, saturation, vibrance, clarity, and mask-aware sharpening controls.
- Basic automatic exposure suggestion for the selected layer.
- Before/after toggle and PNG export.

## Run
Open `index.html` in a modern browser, or use GitHub Pages after merging/deploying this branch.

## Notes
- This is an early MVP. The current auto adjustment uses local image statistics; it is not AI subject recognition.
- The editor downsizes very large images to a maximum working dimension of 2600 px to keep browser memory use manageable.
- Supported input depends on the browser's image decoder. PNG export is currently provided.
- Local adjustments are non-destructive in the sense that the original image pixels are retained in memory and each layer stores its own settings and mask. This initial version does not yet save editable project files between sessions.
