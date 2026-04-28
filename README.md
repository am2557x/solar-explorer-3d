# Solar Explorer — 3D Web Application
## H7006 Web 3D Applications — University of Sussex 2025/26

---

## Project Structure

```
solar/
├── index.html          ← Main 3D app
├── submission.html     ← Submission details
├── README.md           ← This file
├── models/
│   ├── Earth.glb
│   ├── Saturn.glb
│   ├── Mars.glb
│   └── Moon.glb
└── audio/
    └── space-ambient.mp3
```

## How to Run Locally

1. Open the `solar/` folder in **VS Code**
2. Right-click `index.html` → **Open with Live Server**
3. Open in **Chrome** at `http://127.0.0.1:5500/index.html`

## Features

- ✅ Three.js r158 with ES Modules
- ✅ GLTFLoader — 4 real GLB planet models
- ✅ OrbitControls — drag to rotate, scroll to zoom
- ✅ Wireframe toggle (required by brief)
- ✅ Main lighting toggle
- ✅ Rim lighting toggle
- ✅ Launch sequence spin animation
- ✅ Camera reset
- ✅ Surface colour variant swatches per planet
- ✅ HDR Nebula lighting (RGBELoader + ACES tonemapping)
- ✅ Space ambient audio toggle
- ✅ Real telemetry data per planet
- ✅ Content swapping (Explore / About pages)
- ✅ Live UTC clock
- ✅ Animated starfield
- ✅ Responsive layout (900px breakpoint)
- ✅ About page with full documentation
- ✅ Accessibility (ARIA, keyboard nav, reduced-motion)

## Technologies

HTML5, CSS3, JavaScript ES6 Modules, Three.js r158, GLTFLoader, RGBELoader, OrbitControls, GLB/GLTF 2.0, Web Audio API, CSS Grid, Google Fonts

## References

- Three.js: https://threejs.org (MIT)
- Google Fonts: https://fonts.google.com (OFL)
- Earth model: [Add source]
- Saturn model: [Add source]
- Mars model: [Add source]
- Moon model: [Add source]
