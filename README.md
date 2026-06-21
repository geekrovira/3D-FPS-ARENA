# ARENA FURY — 3D First Person Shooter

A browser-based 3D first-person shooter built with Three.js. Fight a single AI opponent in a neon-lit arena — no installs, no plugins, just open the file and play.

---

## How to Play

Open `index.html` in any modern browser (Chrome or Edge recommended).

Click **START BATTLE** on the menu screen to begin.

---

## Controls

| Key | Action |
|-----|--------|
| `↑` | Move forward |
| `↓` | Move backward |
| `←` | Turn left |
| `→` | Turn right |
| `Space` | Shoot |

---

## Gameplay

- You and one AI enemy each start with **100 HP**.
- First to reach 0 HP loses.
- Player bullets deal **20 damage** per hit.
- Enemy bullets deal **12 damage** per hit.
- The enemy chases you, strafes at mid-range, and fires with slight random spread.
- Use the **8 cover pillars** scattered around the arena to block enemy fire.
- After each match, click **PLAY AGAIN** to restart.

---

## Features

- **True first-person 3D** perspective with a visible gun model, bob animation, and recoil kick
- **Neon arena** — dark floor with a blue grid, colored point lights in each corner, and atmospheric fog
- **Humanoid AI enemy** — box-built body with glowing yellow eyes; chases, strafes, and shoots
- **Glowing bullets** — cyan (player) and orange (enemy), each casting a dynamic point light
- **Hit feedback** — screen flashes red when you take damage; enemy flashes white when hit
- **Death burst** — expanding explosion sphere when the enemy is eliminated
- **HUD** — real-time health bars for both sides, kill counter, and damage indicator
- **Cover collision** — pillars physically block movement for both player and enemy
- **Game states** — start menu, active game, and victory/defeat screen

---

## Tech Stack

| Layer | Tool |
|-------|------|
| 3D Rendering | [Three.js r128](https://threejs.org) via CDN |
| Language | Vanilla JavaScript (ES6+) |
| Styling | CSS3 |
| Distribution | Single HTML file — no build step required |

---

## File Structure

```
WeekOne/
└── index.html   — complete game (HTML + CSS + JS in one file)
└── README.md    — this file
```

---

## Browser Compatibility

| Browser | Status |
|---------|--------|
| Chrome 90+ | Recommended |
| Edge 90+ | Supported |
| Firefox 88+ | Supported |
| Safari 15+ | Supported |

WebGL must be enabled (it is by default in all modern browsers).
