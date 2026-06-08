# 🚁 Urban FPV Drone Simulator

An immersive **First-Person View (FPV) drone flight simulator** built entirely with **Three.js** in a single HTML file. Fly through a procedurally generated cityscape with real-time HUD, collision detection, and multiple camera modes.

![Urban FPV Drone Simulator](https://img.shields.io/badge/status-active-success)
![Three.js](https://img.shields.io/badge/Three.js-r160-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## ✨ Features

- **Procedural City** – Randomly generated buildings, trees, streetlights, and road grids
- **Multiple Camera Modes**
  - FPV (First-Person View) – cockpit-style camera
  - Chase – third-person follow camera
  - Cinematic Orbit – free orbit around the drone
- **Real-time HUD** – speed, altitude, battery, flight time, distance, collision counter
- **Collision Detection** – physical collision response with buildings and ground
- **Mini-map** – real-time radar display showing drone position and surroundings
- **Dynamic Clouds** – drifting volumetric clouds
- **Pointer Lock Controls** – precise mouse-based rotation control
- **Visual Effects** – dynamic shadows, building window lights, horizon indicator

## 🎮 Controls

| Key | Action |
|:---:|--------|
| **W** | Move forward |
| **S** | Move backward |
| **A** | Move right (strafe) |
| **D** | Move left (strafe) |
| **Space** | Ascend |
| **Shift** | Descend |
| **Q** | Rotate left |
| **E** | Rotate right |
| **V** | Switch camera mode |
| **Mouse** | Look around (FPV / Chase mode) |
| **Click** | Lock pointer (FPV / Chase mode) |

### Camera Modes

- **FPV (Mode 0)** – First-person view from the drone's perspective
- **Chase (Mode 1)** – Third-person chasing camera (*default*)
- **Cinematic Orbit (Mode 2)** – Free orbital camera controlled by mouse

## 🚀 Getting Started

No build tools required! Just open the file in any modern browser:

1. **Clone or download** this repository
2. Open `index.html` in your browser (Chrome, Edge, or Firefox recommended)
3. Click **"启动飞行" (Start Flight)** to begin
4. Click on the canvas to lock the pointer
5. Fly freely!

> **Note:** Requires a stable internet connection – Three.js is loaded via CDN.

## 🛠️ Technical Stack

- **[Three.js](https://threejs.org/) r160** – 3D rendering engine (loaded via CDN)
- **Vanilla JavaScript (ES Modules)** – no build tools, no frameworks
- **CSS3** – Landing screen, HUD overlays, and visual effects
- **HTML5 Canvas** – Real-time mini-map rendering

## 📁 Project Structure

```
├── index.html          # Main application (everything in one file)
├── LICENSE             # MIT License
├── README.md           # This file (English)
├── README_CN.md        # Documentation (Chinese)
└── .gitignore          # Git ignore rules
```

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit (`git commit -m 'Add some amazing feature'`)
5. Push (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Three.js](https://threejs.org/) community for the amazing 3D library
- Inspired by real FPV drone flying experiences
- Built with ❤️ for drone enthusiasts and web developers