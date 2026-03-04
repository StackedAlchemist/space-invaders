# 👾 Cosmic Rift Defender

> *"The rift has opened. The void pours through. Hold the line."*

A neon-charged Space Invaders-style arcade game built with the HTML5 Canvas API. Features particle explosions, progressive difficulty, enemy AI patterns, and full mobile touch controls.

**[🎮 Play Now](https://stackedalchemist.github.io/stacked-alchemist/space-invaders/index.html)**

---

## ✦ Features

- **Canvas-Based Rendering** — Smooth 60fps game loop using `requestAnimationFrame`
- **Progressive Difficulty** — Enemies speed up as their numbers thin; difficulty increases each wave
- **Particle Explosions** — Custom particle system on enemy and player destruction
- **Enemy AI** — Formation movement with descending dive patterns
- **Power-ups** — Collectible drops that enhance player abilities
- **Multiple Difficulty Modes** — Easy, Normal, and Hard
- **Mobile Controls** — On-screen touch buttons for mobile play
- **High Score Tracking** — Top scores saved to localStorage
- **Sound Effects** — Web Audio API generated sounds

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 Canvas | All rendering |
| Vanilla JavaScript (ES6 Modules) | Game logic, entity management |
| Web Audio API | Sound effects |
| localStorage | High score persistence |
| CSS3 | UI overlays and menus |

---

## 🎮 Controls

| Action | Keyboard | Mobile |
|---|---|---|
| Move Left | `←` or `A` | Left button |
| Move Right | `→` or `D` | Right button |
| Shoot | `Space` | Fire button |
| Pause | `P` | Pause button |

---

## 🚀 Running Locally

```bash
git clone https://github.com/StackedAlchemist/Portfolio.git
cd Portfolio/space-invaders
# Open index.html in your browser
```

> **Note:** ES6 modules require a local server to run correctly. Use VS Code's Live Server extension or `npx serve .`

---

## 📁 File Structure

```
space-invaders/
├── index.html    # Game shell
├── style.css     # UI styles
├── game.js       # Main game loop and state management
├── player.js     # Player entity
├── enemy.js      # Enemy entity and AI
└── bullet.js     # Projectile logic
```

---

*Built by [Billy Williams](https://stackedalchemist.github.io/Portfolio/) — Stacked Alchemist*
