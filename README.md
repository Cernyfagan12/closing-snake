# Closing Snake

A browser Snake game where the arena keeps shrinking. Every 15 seconds (on Normal) the walls move in by one cell, until the arena is 9×9.

## How to play

Open `index.html` in any modern browser. You don't need to build or install anything.

| Action | Keys |
| --- | --- |
| Move | Arrow keys or WASD (swipe on a phone) |
| Start / pause / resume | Space |
| Mute / unmute | M, or the 🔊 button (remembered between visits) |

## Difficulty

Pick a level on the start or game-over screen. Each level keeps its own best score.

| Level | Walls close every | Snake speed |
| --- | --- | --- |
| Easy | 20 s | slower |
| Normal | 15 s | standard |
| Hard | 10 s | faster |
| 📅 Daily | 15 s | standard |

**Daily challenge:** the date picks the apples, so everyone gets the same apples in the same order that day. It keeps a separate "best today" score that resets at midnight, plus a 🔥 streak of days in a row you've played.

## 🗺️ Stages

Press **🗺️ Stages** to play through 14 stages in two worlds. Eat the goal number of apples to clear a stage. You earn bonus coins and unlock the next stage. The walls still close in, so be quick!

**World 1 · Neon City:** crystal obstacles.

| # | Stage | Goal |
| --- | --- | --- |
| 1 | Warm-up | 5 🍎 |
| 2 | Pillars | 8 🍎 |
| 3 | Bars | 10 🍎 |
| 4 | Columns | 12 🍎 |
| 5 | Corners | 14 🍎 |
| 6 | Fortress | 16 🍎 |
| 7 | Zigzag | 18 🍎 |

**World 2 · Portal Lab:** step into a swirling portal and you come out of its partner. A portal stops working (it goes dim) once the walls close over either end.

| # | Stage | Goal |
| --- | --- | --- |
| 8 | First Jump | 10 🍎 |
| 9 | Crossroads | 12 🍎 |
| 10 | Split | 14 🍎 |
| 11 | Gatehouse | 16 🍎 |
| 12 | Twin Rooms | 18 🍎 |
| 13 | Zigzag Lab | 20 🍎 |
| 14 | Core | 22 🍎 |

## 🏅 Achievements

14 achievements, each paying bonus coins once: eat 1 / 50 / 250 apples, catch 10 golden apples, score 200 / 500 in one game, score 100 on Hard, survive until the walls stop closing, get saved by a shield, reach a 3-day daily streak, own 4 skins, clear all stages, rebirth once, and jump through 25 portals. Press **🏅** on the start or game-over screen to see your progress.

## Coins, skins and upgrades

Every game earns 🪙 1 coin per 10 points. Spend coins in the **🛒 Shop** (on the start and game-over screens).

**Skins:** Ocean, Fire, Candy, Midnight, Gold, and an animated Rainbow. You buy each skin once and can switch skins anytime.

**Upgrades:**

| Upgrade | Effect | Price |
| --- | --- | --- |
| ⏱️ Longer powers | Powers last 7 → 9 → 11 → 13 s | 40 / 80 / 150 |
| ⭐ More golden apples | Golden apple chance 35% → 45 → 55 → 65% | 50 / 100 / 180 |
| 🪙 Coin bonus | +10% / +20% / +30% coins | 60 / 120 / 200 |
| 🐌 Steady pace | The snake speeds up 15% / 30% / 45% less with each apple | 50 / 100 / 180 |
| 🧱 Slower walls | Walls close 1 / 2 / 3 s later | 60 / 120 / 200 |
| 🍀 Lucky star | Golden stars stay 7.5 / 9 / 10.5 s | 40 / 80 / 150 |
| 🛡️ Shield | Saves you from one crash, then it's used up (hold up to 5) | 25 each |

**🌟 Rebirth:** once every upgrade above is maxed, you can rebirth. Your coins and upgrades reset, but you get **+25% coins forever** for each rebirth (×1.25, ×1.5, ×1.75…). Skins, stages, achievements and shields stay.

If you own a shield, one is ready at the start of each game. When it saves you from a wall or your own tail, the snake stops for a moment so you can turn away. If the walls would crush you, it holds them back.

## Rules

- 🍎 **Red apple**: +10 points, and the snake grows by one. The snake speeds up with every apple.
- ⭐ **Golden apple**: +25 points and a random 7-second power. It disappears after 6 seconds.
  - 🐢 Slow-mo: the snake moves more slowly
  - 👻 Ghost: pass through your own tail
  - ✖2 Double points
  - 🧱 Push walls back: the walls move out by one cell (only once they've closed in)
- 🟥 Cells that blink red will become wall in 3 seconds. Get out of them.

You lose if you hit a wall, bite your own tail, or get crushed by a closing wall. Your best score is saved in the browser.
