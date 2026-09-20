# Subway Dash - 3D Urban Endless Runner 🚇

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Web Audio](https://img.shields.io/badge/Web_Audio-API-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Vercel](https://img.shields.io/badge/Deployed-Vercel-black.svg)](https://subway-surfers-clone-one.vercel.app)

> **DODGE THE TRAINS • CHASE THE GOLD • DEFY THE RAILS**

A high-speed 3D urban endless runner inspired by Subway Surfers, engineered from scratch with vanilla HTML5 Canvas, JavaScript, and synthesized procedural audio via the Web Audio API. Zero dependencies, zero build step—instant 60 FPS gameplay on desktop and mobile.

---

## 🚀 Live Demo

You can play the live deployment here:  
**👉 [https://subway-surfers-clone-one.vercel.app](https://subway-surfers-clone-one.vercel.app)**

*(Alternative GitHub Pages Mirror: [https://shriyanshthanneeru2407-dotcom.github.io/subway-surfers-clone/](https://shriyanshthanneeru2407-dotcom.github.io/subway-surfers-clone/))*

> **No installation required!** Click the link to jump straight onto the tracks. High scores and audio settings are saved directly in your browser.

---

## 📂 GitHub Repository

You can access the open-source repository here:  
**👉 [https://github.com/shriyanshthanneeru2407-dotcom/subway-surfers-clone](https://github.com/shriyanshthanneeru2407-dotcom/subway-surfers-clone)**

---

## ✨ Features

- **🌐 Zero External Dependencies**: 100% self-contained single-file deployment. No heavy game engines, bundlers, or third-party libraries required.
- **⚡ 60 FPS Perspective 3D Engine**: Custom vanishing-point depth projection renders realistic curved track ballast, dual steel rails, wooden sleepers, and roadside sodium-vapor lamps.
- **🌆 Parallax Cyberpunk Skyline**: Layered cityscape featuring ambient star twinkling, rooftop antennas, and responsive sunset twilight lighting.
- **🏃 Dynamic Character State Machine**: Smooth quadratic lane-switching, authentic gravity jump physics with tucked legs, and low-clearance rolling animations.
- **🔊 Web Audio API Sound Engine**: Real-time synthesized SFX for jumps, rolls, lane shifts, coin grabs, power-up chimes, and crash impacts.
- **📱 Cross-Platform Input**: Seamless support for desktop keyboard controls (`Arrow Keys`, `WASD`, `Space`) and mobile touch/swipe gestures.
- **💾 Local Score Persistence**: Automatically tracks and persists personal best high scores in the browser via `localStorage`.

---

## 🎮 Gameplay & Mechanics

### 🚧 Obstacles
- 🚂 **Subway Trains**: Full-scale oncoming express trains equipped with headlights, windshield glare, and caution chevron hazard stripes.
- 🚧 **Track Barriers**: Low hurdles requiring timed jumps.
- 🔲 **Overhead Beams**: Low-clearance industrial gantries marked with `▼ DUCK! ▼` warnings requiring crouch rolls or mid-air dives.

### ⚡ Power-Ups & Buffs
- 🛡️ **Energy Shield**: Absorbs a lethal impact, triggers protective invulnerability frames, and keeps the run alive.
- 🧲 **Coin Magnet**: Powerful magnetic aura drawing gold coins from all three lanes simultaneously.
- ⚡ **2× Multiplier**: Doubles distance points and coin rewards for the duration of the buff.
- 🪙 **Gold Coins**: 3D spinning gold coins placed in dynamic straight, wave, and parallel formations.

---

## 🕹 Controls

| Action | Keyboard | Touch / Mobile |
| :--- | :--- | :--- |
| **Move Left** | `←` or `A` | Swipe Left |
| **Move Right** | `→` or `D` | Swipe Right |
| **Jump** | `↑` or `W` or `Space` | Swipe Up / Tap |
| **Roll / Dive** | `↓` or `S` | Swipe Down |

---

## 🚀 Quick Start & Local Development

Run locally without any installation:

```bash
# 1. Clone the repository
git clone https://github.com/shriyanshthanneeru2407-dotcom/subway-surfers-clone.git
cd subway-surfers-clone

# 2. Open directly in browser (macOS)
open index.html

# Or serve locally with Python
python3 -m http.server 8080
```
Open `http://localhost:8080` in your browser.

---

## 🛠 Tech Stack

- **HTML5 Canvas 2D / 2.5D**: Custom 3D perspective projection and sprite rendering pipeline.
- **Vanilla JavaScript (ES6+)**: Delta-timing game loop, collision detection, particle physics, and state machines.
- **Web Audio API**: Hardware-accelerated dynamic oscillator and gain sound synthesis.
- **Modern CSS**: Glassmorphism backdrop filters (`backdrop-filter: blur(14px)`), neon glows, and responsive container scaling.

---

## 👨‍💻 Author & Copyright

- **Creator & Engineer**: **Shriyansh Thanneeru**
- **Copyright**: © 2026 Subway Dash. All rights reserved.
