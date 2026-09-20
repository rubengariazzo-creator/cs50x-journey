# cs50x-journey

Public progress log for Harvard's CS50x: which problem sets I've completed, plus my own short reflections on what I learned.

**No solution code lives in this repo.** Per CS50's academic honesty policy, sharing problem set solutions publicly while enrolled is not allowed. This repo only tracks completion status and personal reflections, never actual code.

## How this works

- `progress.json` lists each week/problem set, whether I've completed it, and a short reflection.
- Pushing a change to `progress.json` triggers a GitHub Actions workflow that notifies my portfolio site, which rebuilds and shows an updated progress bar automatically.

## Editing progress.json

Each entry looks like this:

```json
{ "title": "Week 0: Scratch", "completed": false, "reflection": "" }
```
Set `completed` to `true` once a week is done, and fill in `reflection` with a sentence or two about what you learned. No dates, no code.
