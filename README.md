# Smart Object Identifier

Responsive frontend-only object detector using HTML5, CSS3, JavaScript, TensorFlow.js and COCO-SSD.

## Run
1. Extract this ZIP and open the folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` → **Open with Live Server**.
4. Allow camera permission, click **Start camera**, then **Detect objects**. You can also upload an image.

Alternative: run `python -m http.server 5500` in this folder and open `http://localhost:5500`.

## Features
- Camera access (prefers rear camera on phones; webcam on desktop).
- Common-object detection with confidence scores and bounding boxes.
- Image upload alternative.
- Responsive interface and camera/model error handling.
- Image processing occurs in the browser; no app backend or API key.

## Requirements and limitations
- HTTPS or localhost is required for camera access.
- Internet is required to load TensorFlow.js and the COCO-SSD model from jsDelivr.
- Detects a fixed set of common object classes, not every possible object. Results may be inaccurate.
- Test using current Chrome or Edge.
