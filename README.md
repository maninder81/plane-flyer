# ✈ Flight Game

A 3D plane / survival game built with [Three.js](https://threejs.org/) — runs entirely in the browser, no build step.

**Modes**
- **Practice** — free flight over a huge procedurally-generated planet.
- **Maze** — race through mountains to the finish line; times saved to a local leaderboard.
- **Story** — zombie-apocalypse survival: fly by day, drive & fight by night, loot buildings, build a safe house.

## Run locally
Just open `index.html` in a browser, or serve the folder:
```
py -m http.server 5599
```
then visit http://localhost:5599

## Deploy
Static site — any host works. On Vercel, no configuration is needed (the root `index.html` is served automatically).
