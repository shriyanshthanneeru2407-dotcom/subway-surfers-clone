# Subway Dash 🚇

A Subway Surfers-style 3D endless runner built with pure HTML5 Canvas and JavaScript. Zero external libraries, zero installation required—just open and play!

![Subway Dash](screenshot_preview.png)

## 🎮 Features

- **Perspective 3D Track**: Dynamic vanishing-point track projection featuring railway tracks, wooden ties, glowing neon lane markers, and atmospheric lampposts.
- **Parallax Cyberpunk Skyline**: Layered cityscape background with glowing windows, twinkling stars, and sunset horizon.
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

---

## 📄 License

MIT License. Free to use, modify, and build upon.
