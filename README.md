# Tom & Jerry 3D VR World

A simple, interactive, 3D browser-based Virtual Reality experience of a cartoon world inspired by Tom and Jerry. Built using the [A-Frame](https://aframe.io/) WebVR framework.

## 🌟 Features
* **WebVR Ready**: Works in your browser on PC, Mobile, and VR Headsets (like Meta Quest).
* **3D Models**: Includes primitive shapes arranged to resemble Tom, Jerry, and classic cartoon props (giant cheese, anvil, red mallet, and a bowling ball).
* **Interactive Camera**: Move around the 3D space using WASD keys and look around using mouse drag or device orientation (on mobile).

## 🚀 How to Run

Because this is a static HTML file that loads external assets and scripts via CDNs, it is incredibly easy to run!

### Method 1: Direct Open (Easiest)
1. Navigate to the folder containing these files.
2. Double-click on `index.html`.
3. It should open directly in your default web browser (Chrome, Edge, or Firefox recommended).

### Method 2: Local Web Server (Recommended for VR Headsets)
If you want to view this on a standalone VR headset or if you run into any CORS (Cross-Origin Resource Sharing) issues loading textures:
1. If you have Python installed, open a terminal in this directory and run: 
   ```bash
   python -m http.server 8000
   ```
2. If you have Node.js, you can use `npx`:
    ```bash
    npx serve .
    ```
3. Open your browser and go to `http://localhost:8000` (or the port specified by your tool).

## 🕹️ Controls
* **Desktop**: Click and drag to look around. Use `W, A, S, D` or Arrow keys to move your camera position.
* **Mobile**: Move your phone around to look (requires device sensors permission) or drag the screen. Tap the "VR" icon to enter full-screen VR mode if using a headset attachment.
* **VR Headset**: Click the "VR" button in the bottom right corner of the browser window to enter immersive mode. Use your controllers to point and navigate.

## 🛠️ Technologies Used
* **HTML/CSS** for the overlay UI and document structure.
* **A-Frame (v1.5.0)**: A web framework for building virtual reality experiences.
* **A-Frame Environment Component**: Used to quickly generate the colorful "dream" preset world backdrop.
