# Subway Dash 🚇

> **DODGE THE TRAINS • CHASE THE GOLD • DEFY THE RAILS**

A high-octane 3D endless runner clone of Subway Surfers engineered with pure HTML5 Canvas and JavaScript. Zero external libraries, zero installation required—just open and play!

---

## ⚡ About The App

**Subway Dash** is an adrenaline-fueled 3D endless runner built for lightning-fast reflexes and street style. Dash across high-voltage tracks, dodge oncoming subway trains, leap over barricades, and roll underneath industrial beams. Collect gold coins, harness magnetic fields, trigger protective shields, and unlock score multipliers to shatter records!

---

## 🎮 Key Features & Highlights

- **Perspective 3D Track**: Dynamic vanishing-point track projection featuring realistic railway tracks, wooden ties, glowing neon lane markers, and roadside lampposts.
- **Parallax Cyberpunk Skyline**: Layered cityscape background with glowing windows, twinkling stars, and sunset horizon with ambient motion on menus.
- **Authentic Runner Controls**:
  - **3-Lane Navigation**: Fluid quadratic interpolation between lanes.
  - **Jump & Landing**: Smooth gravity physics, tucked-leg jumping animation, and dust puffs on landing.
  - **Roll / Duck**: Low roll posture to slide under clearance obstacles, plus rapid downward dive from mid-air.
- **Obstacles**:
  - 🚂 **Subway Trains**: Full-height trains with glowing dual headlights, windshield reflections, and caution hazard stripes.
  - 🚧 **Barriers**: Low hurdles requiring jumping.
  - 🔲 **Overhead Beams**: Low clearance beams requiring crouching/rolling.
- **Collectibles & Power-Ups**:
  - 🪙 **Coins**: 3D spinning gold coins in varied lane formations.
  - 🛡 **Shield**: Energy barrier providing collision protection and invulnerability frames.
  - 🧲 **Coin Magnet**: Pulls coins toward you across all lanes.
  - ⚡ **2× Multiplier**: Doubles distance and coin score rewards.
- **Procedural Audio (Web Audio API)**: Sound effects synthesized on-the-fly for jumps, rolls, lane switches, coin grabs, power-ups, and crashes—no external audio files needed!
- **Cross-Platform Input**: Full support for Keyboard (Arrows / WASD / Space) and Mobile touch/swipe gestures.
- **Local Persistence**: Saves your personal high score locally using `localStorage`.

---

## 🕹 Controls

| Action | Keyboard | Touch / Mobile |
| :--- | :--- | :--- |
| **Move Left** | `←` or `A` | Swipe Left |
| **Move Right** | `→` or `D` | Swipe Right |
| **Jump** | `↑` or `W` or `Space` | Swipe Up / Tap |
| **Roll / Dive** | `↓` or `S` | Swipe Down |

---

## 🚀 Getting Started

Simply open `index.html` in any modern web browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

Or serve locally with Python:

```bash
python3 -m http.server 8080
```
Then visit `http://localhost:8080`.

---

## 🛠 Tech Stack

- **HTML5 Canvas API**: Custom 2.5D/3D perspective projection and sprite rendering.
- **Vanilla JavaScript**: State machine, delta-time game loop, collision detection, and procedural particle engines.
- **Web Audio API**: Real-time sound effect synthesis.
- **Glassmorphic UI**: High-definition CSS backdrop filters, responsive flex layout, and fluid typography.

---

## 👨‍💻 Author & Credits

**ENGINEERED & DESIGNED BY**  
### **Shriyansh Thanneeru**

---

## 📄 License & Rights

© 2026 Subway Dash. All Rights Reserved.
