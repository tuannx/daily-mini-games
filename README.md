# Daily Mini-Games 🎮

A new tiny browser game, built and published **every day** on GitHub Pages.

**Play:** https://tuannx.github.io/daily-mini-games/

## How it works

- Each day, trending mini-game mechanics are researched from social/web (one-tap runners, physics chaos, merge puzzles, typing combat, idle clickers, hybrid mashups…).
- One mechanic is picked and built as a **single self-contained HTML file** (vanilla Canvas + JS, zero dependencies, mobile + desktop controls).
- The game is appended to `games.json`, committed, and pushed — GitHub Pages redeploys automatically.
- Old games stay playable forever. Same shell, new game daily.

## Catalog

See `games.json` for the machine-readable list; the landing page renders it.

## Local play

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```
