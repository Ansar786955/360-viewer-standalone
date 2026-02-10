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
2. **Important Note**: Browsers block local files (`file://`) from loading for security. You **MUST** run a local server:

### Option 1: Simple Server (Python)
- Open the folder where you extracted the ZIP.
- Open Terminal/Command Prompt in that folder.
- Run: `python -m http.server 8000`
- Open Browser and go to: `http://localhost:8000/360_standalone.html`

### Option 2: VS Code (Live Server)
- Open the folder in VS Code.
- Install "Live Server" extension.
- Click "Go Live" at the bottom right.

### Option 3: Local Server Executable
- If you don't have Python, you can use any small web server program like `http-server` (Node.js) or `Servez`.

## Direct Download
[Download viewer_code.zip](./viewer_code.zip)
