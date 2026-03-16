# Tap Frenzy 🎯

A lightweight, mobile-first tap/clicker game built as a single, zero-dependency HTML file.

## How to play

Open `index.html` in any modern browser (desktop or mobile) — no build step, no server required.

- **Tap** the colourful circles before they disappear.
- **Build combos** by tapping multiple circles in quick succession (up to ×5 multiplier).
- You have **30 seconds** — score as high as you can!

## Scoring

| Action | Points |
|--------|--------|
| Tap a circle | 10 × current combo multiplier |
| Miss a circle | Combo resets to ×1 |

Score thresholds and messages:

| Score | Message |
|-------|---------|
| 0+ | Keep practicing! 💪 |
| 30+ | Not bad! 👍 |
| 60+ | Nice work! 🎯 |
| 100+ | Great reflexes! ⚡ |
| 150+ | Amazing! 🔥 |
| 200+ | Unbelievable! 💎 |

## Difficulty scaling

The game gets harder as time passes:

- **Spawn rate** speeds up from one circle every ~900 ms down to one every 400 ms.
- **Target lifespan** shrinks from ~1800 ms down to 800 ms.

## Tech stack

| | |
|--|--|
| Language | Vanilla JavaScript |
| Markup | HTML5 |
| Styling | Embedded CSS3 |
| Dependencies | None |
| Build process | None |

The entire game is contained in **`index.html`** (~400 lines).
