# 360 Viewer Project

This project provides a standalone 360-degree image viewer using Marzipano.

## Files
- `360_standalone.html`: The main viewer page.
- `360_viewer.js`: Logic for the 360 viewer.
- `360_viewer_data.js`: Configuration and scene data.
- `360_viewer.css`: Styling for the viewer.
- `tiles/`: Directory containing image tiles for the 360 view.
- `img/`: Icons for controls.
- `vendor/`: Third-party libraries (Marzipano, Bowser, Screenfull).

## How to run locally
1. **Extract the ZIP**: Unzip `viewer_code.zip` on your computer.
2. **Open the HTML**: Right-click on `360_standalone.html` and select "Open with" -> "Google Chrome" (or your preferred browser).
3. **Important Note**: Some browsers block local files from loading images for security. If the viewer is empty, you need to run a small local server:
   - If you have Python: Open terminal in the folder and run `python -m http.server 8000`, then go to `http://localhost:8000/360_standalone.html`.
   - If you have VS Code: Use the "Live Server" extension.

## Direct Download
[Download viewer_code.zip](./viewer_code.zip)
