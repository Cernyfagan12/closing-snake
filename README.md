# Closing Snake

A browser Snake game where the arena keeps shrinking. Every 15 seconds the walls move in by one cell, until the arena is 9×9.

## How to play

Open `index.html` in any modern browser. You don't need to build or install anything.

| Action | Keys |
| --- | --- |
| Move | Arrow keys or WASD (swipe on a phone) |
| Start / pause / resume | Space |
| Mute / unmute | M, or the 🔊 button (remembered between visits) |

## Rules

- 🍎 **Red apple**: +10 points, and the snake grows by one. The snake speeds up with every apple.
- ⭐ **Golden apple**: +25 points and a random 7-second power. It disappears after 6 seconds.
  - 🐢 Slow-mo: the snake moves more slowly
  - 👻 Ghost: pass through your own tail
  - ✖2 Double points
  - 🧱 Push walls back: the walls move out by one cell (only once they've closed in)
- 🟥 Cells that blink red will become wall in 3 seconds. Get out of them.

You lose if you hit a wall, bite your own tail, or get crushed by a closing wall. Your best score is saved in the browser.
