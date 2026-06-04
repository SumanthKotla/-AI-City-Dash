# 🤖 AI City Dash

> **San Francisco is falling — Run before the robots take over.**

A fast-paced, cyberpunk side-scrolling runner built entirely in a single HTML file. Sprint through 4 iconic San Francisco districts, from the Financial District to the Golden Gate, collecting data coins, dodging AI robots, and racing to upload your payload before the city falls to machine control.

---

## 🎮 Play It

Just open `index.html` in any modern browser. No install, no dependencies, no build step.

```bash
git clone https://github.com/your-username/ai-city-dash.git
cd ai-city-dash
open index.html
```

---

## 🕹️ Controls

| Action | Key |
|---|---|
| Jump | `Space` / `↑` |
| Double Jump | Press Jump twice |
| Move Left / Right | `←` `→` |
| Boost | `Shift` |
| Pause | `P` |

---

## 🌆 The Mission

An AI uprising has seized San Francisco. You're a data courier — the last human who can reach the secure server and upload the kill-switch payload. Sprint through 4 districts, grab every coin you can, and don't let the robots touch you.

### Districts
1. 🏦 **Financial District** — Where the chaos began
2. 💻 **SoMa Tech Hub** — Ground zero of the AI outbreak
3. 🌮 **Mission District** — Street-level robot patrols
4. 🌉 **Golden Gate** — Final sprint to the server

---

## ⚙️ Difficulty Modes

| Mode | Robots | Lives | Finish Distance |
|---|---|---|---|
| 🏙️ **Easy** | Few, slow | 3 | Short |
| 🤖 **Medium** | City in panic | 3 | Long |
| 💀 **Hard** | Full robot army | 2 | Extreme |

---

## ✨ Features

- **Fully self-contained** — one `index.html` file, zero dependencies
- **Animated title screen** — live SF skyline with AI glitch effects, lightning, and scanlines
- **Dynamic parallax world** — multi-layer scrolling city with hand-drawn canvas art
- **AI Threat System** — threat level rises as you progress; screen glitches and warnings kick in
- **Energy & Boost bars** — manage your shield and sprint meter strategically
- **Score popups & confetti** — satisfying feedback on coin grabs and level completion
- **Win screen stats** — final score, best score, districts cleared, and difficulty badge
- **Local best score** — tracks your high score across sessions
- **Responsive** — adapts to any screen size

---

## 🛠️ Tech Stack

| Layer | Details |
|---|---|
| Runtime | Vanilla JavaScript (ES2020) |
| Rendering | HTML5 Canvas 2D API |
| Fonts | Google Fonts — Orbitron, Exo 2 |
| Styling | Pure CSS (no framework) |
| Build | None — open and play |

---

## 📁 Project Structure

```
ai-city-dash/
└── index.html   # The entire game — engine, assets, UI, and styles
```

---

## 🚀 Customization

Everything lives in one file, making it easy to hack on:

- **Difficulty tuning** — tweak the `DIFF` object near the top of the `<script>` tag (meteor count, speed, lives, finish distance)
- **Districts** — edit the `DISTRICTS` array to rename or add zones
- **Colors & fonts** — all CSS variables and gradients are at the top of the `<style>` block
- **Physics** — `GRAVITY`, `JUMP_FORCE`, and `MOVE_SPEED` constants are clearly labeled

---

## 📄 License

MIT — do whatever you want with it. Just don't let the robots win. 🤖

---

<p align="center">
  Built with ☕ and existential dread about AI takeovers.
</p>
