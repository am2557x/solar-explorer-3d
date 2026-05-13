# Solar Explorer — H7006 Web 3D Applications
**University of Sussex · 2025/26 · Abdulrhman Makki (589064)**

---

Solar Explorer is my final project for H7006. It's an interactive 3D space app built with Three.js where you can explore four planets — Earth, Saturn, Mars and the Moon — rendered as real GLB models inside a mission control style interface. You can rotate and zoom around each one, switch between them, toggle wireframe, change lighting, pick surface colour variants and trigger an orbit spin animation. There's a telemetry panel on the right showing real data for each planet and a space ambient audio track you can switch on.

The design is inspired by NASA mission control and sci-fi HUDs — dark navy background, electric blue glows, monospace fonts, corner bracket overlays and a scanning line across the viewport.

---

## How to run it

1. Open the `solar/` folder in VS Code
2. Right-click `index.html` → Open with Live Server
3. View in Chrome at `http://127.0.0.1:5500/index.html`

---

## What's in the project

```
solar/
├── index.html          ← Main 3D app
├── submission.html     ← Submission details and links
├── README.md           ← This file
├── models/
│   ├── Earth.glb
│   ├── Saturn.glb
│   ├── Mars.glb
│   └── Moon.glb
├── images/
│   ├── earth_blender.png
│   ├── saturn_blender.png
│   ├── mars_blender.png
│   └── moon_blender.png
└── audio/
    └── space-ambient.mp3
```

---

## Tech stack

Three.js r158, GLTFLoader, RGBELoader, OrbitControls, ACES Filmic Tonemapping, Web Audio API, HTML5, CSS3, JavaScript ES6 Modules, CSS Grid, Google Fonts (Orbitron + Space Mono)