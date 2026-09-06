# 🕹️ Arcade Hub

A curated collection of standalone, single-file browser games built with pure web technologies and WebGL.

Every game runs entirely client-side with **zero dependencies, build steps, or installations required**.

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/Web_Audio_API-4A90E2?style=for-the-badge" alt="Web Audio API" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
</p>

---

## 🎮 Game Roster

| Game                | Description                                                                                                                                      | Tech Stack                     |       Status      |
| :------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------- | :---------------: |
| **Temple Relic 3D** | High-fidelity 3D endless runner. Jump over ancient ruins, slide under iron portcullises, and collect sacred gold coins across procedural tracks. | `Three.js` `Web Audio` `WebGL` |    🟢 Playable    |
\
> 💡 Add more games to the roster as the collection grows.

---

## ✨ Core Features

* 🚀 **Zero Setup** — Every title is self-contained within an `.html` file. Double-click and play in any modern browser.
* 📦 **No External Assets** — Models, textures, animations, and sound effects are generated procedurally at runtime.
* 🎨 **Pure Web Technologies** — Built with HTML5, CSS3, JavaScript, Canvas, WebGL, and Web Audio.
* 📱 **Cross-Device Ready** — Responsive layouts with mouse, keyboard, touch, and swipe controls.
* ⚡ **Fast Performance** — Lightweight architecture with hardware-accelerated WebGL rendering.
* 🔌 **No Build Pipeline** — No package manager, compilation, bundler, or installation required.

---

## 🚀 Getting Started

### ▶️ Play Locally

Clone the repository:

```bash
git clone https://github.com/nexus-being-787/Click-2-Play.git
cd Click-2-Play

```

Open any game directly in your preferred browser:

**Windows**

```bash
start games/temple-relic/index.html
```

**macOS**

```bash
open games/temple-relic/index.html
```

**Linux**

```bash
xdg-open games/temple-relic/index.html
```

You can also open `index.html` to launch the main Arcade Hub interface.

---

### 🌐 Optional: Local Development Server
**Only for react**

For development or testing through a local HTTP server:

**Python**

```bash
python -m http.server 8000
```

**Node.js**

```bash
npx serve .
```

Then open:

```text
http://localhost:8000
```

---

## 📁 Repository Structure

```text
Arcade-Hub/
├── assets/
│   └── previews/             # Game previews, icons, and shared assets
│
├── games/
│   ├── temple-relic/         # 3D Endless Runner
│   │   └── index.html
│   │
│   ├── cyber-rush/           # 2D Synthwave Platformer
│   │   └── index.html
│   │
│   └── cosmic-defender/      # Retro Arcade Shooter
│       └── index.html
│
├── index.html                # Main Arcade Hub launcher
├── README.md
└── LICENSE
```

---

## 🛠️ Built With

### HTML5 & CSS3

Used for responsive layouts, game interfaces, full-screen canvas containers, HUD elements, and visual effects.

### Vanilla JavaScript

The games use modern JavaScript (ES6+) for:

* Game loops
* Physics simulation
* Collision detection
* Procedural generation
* Input handling
* Game state management
* UI interactions

### Three.js

Used by 3D games for:

* Real-time 3D rendering
* Scene management
* Lighting
* Shadows
* Camera systems
* Procedural environments

### Web Audio API

Used for lightweight procedural audio generation without requiring external sound files.

---

## 🎯 Design Philosophy

Arcade Hub follows a simple principle:

> **Open → Play → Have Fun.**

There should be no complicated installation process, no dependency setup, and no build pipeline between the player and the game.

Each game is designed to remain lightweight, portable, and easy to share.

---

## 📌 Roadmap

* [ ] Add more arcade games
* [ ] Improve mobile controls
* [ ] Add local high-score storage
* [ ] Add sound and music settings
* [ ] Improve 3D procedural environments
* [ ] Add game thumbnails to the launcher
* [ ] Add fullscreen support
* [ ] Add more WebGL-based games

---

## 📄 License

This project is licensed under the **MIT License**.

See the [`LICENSE`](LICENSE) file for details.
