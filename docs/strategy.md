# Open-Meowdoku strategy guide

**Practice on the live board → [guessingame.org/meowdoku](https://guessingame.org/meowdoku?utm_source=github&utm_medium=docs&utm_campaign=strategy)**

These patterns work on Daily and Levels. They are deduction habits, not spoilers for a specific puzzle.

## Priority order

1. **Tiny regions** — a 2–3 cell region often forces the cat immediately.
2. **Forced rows/columns** — after a placement, check if a line has only one safe cell left.
3. **Neighbor walls** — every cat forbids its Moore neighborhood (8 cells). Mark them.
4. **Region vs column collisions** — if two regions both “want” the same column, find the contradiction early.
5. **Hints last** — hints teach less than a clean elimination pass.

## Marking discipline

- Turn on auto-mark in Settings if available.
- After every placement, mark: same row, same column, adjacent cells, and filled-region leftovers.
- Never place into a marked cell “just to try” — undo instead.

## Common traps

| Trap | Fix |
|------|-----|
| Forgetting diagonal adjacency | Treat every cat like a king in chess: no king-move neighbors |
| Filling a pretty region first | Check column/row collisions before committing |
| Burning the hint early | Mark first; hint when two candidates remain |
| Resetting too soon | Undo 1–2 moves; the board state is usually salvageable |

## Speed tips for Daily

- Start top-left or at the smallest region cluster — whichever has the fewest open cells.
- Speak the four rules once out loud on hard boards; it cuts careless diagonal mistakes.
- Compare times later via Ranking on the same device — Daily is shared by calendar day.

## Keep improving

Play a few Levels after Daily to stretch board size:

**[→ Open Guessingame Meowdoku](https://guessingame.org/meowdoku?utm_source=github&utm_medium=docs&utm_campaign=strategy)**
