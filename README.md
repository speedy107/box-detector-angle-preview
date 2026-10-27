# Box Detector Angle Preview

Preview branch for the cube outer-edge overlay and horizontal deviation angle.

- **Preview:** https://speedy107.github.io/box-detector-angle-preview/
- **Source:** https://github.com/speedy107/box-detector-angle-preview
- **Original site (left unchanged):** https://speedy107.github.io/box-detector-compare/

The preview adds a **Show cube outer edges + deviation angle** toggle. It estimates a cube's deviation from a head-on view using the fitted cube pose. This is experimental and should be checked against known camera angles before being used for robotics decisions.

To keep the new preview repository lightweight, the ONNX model and large WASM/OpenCV runtime assets are loaded from the original public Pages site. The code changes and deployment workflow live in this repository; the original repository's files and Pages deployment are not modified.

## Enable GitHub Pages once

In this repository, open **Settings → Pages → Build and deployment**, choose **GitHub Actions** as the source, and save. Then open **Actions → Deploy cube-angle preview to GitHub Pages** and rerun the latest workflow if it does not start automatically.

The browser needs camera permission and HTTPS for live-camera mode. You can also choose a photo for testing.
