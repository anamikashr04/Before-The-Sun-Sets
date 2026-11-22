# Before the Sun Sets

A first-person, photographic time-loop game. Notice clues, borrow an animal's senses, and guide the pangolin to the refuge before sunset.

## Publish on GitHub Pages
1. Create a new public repository. GitHub's website takes up to 100 files per upload, so upload in two goes: first `index.html`, `assets` and `video`; then, optionally, `ui-frames`, `reference-images` and this README.
2. Go to Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, and save.
3. After about a minute, GitHub shows the game's link at the top of the Pages settings.

To test on your own computer, run a small local server in this folder (for example `python3 -m http.server`) and open http://localhost:8000. Opening the file directly also works in most browsers.

## Controls
W/S or Up/Down: walk on / step back. A/D or Left/Right: turn onto a side path. Mouse: look around (click the view to lock the mouse). E: inspect or talk. 1 to 4, P, Q, Tab or the mouse wheel: switch sense (Human, Bird, Frog, Leopard). M: map. J: journal. I: info. T (hold): let time pass. Esc: pause.

## Files
- `index.html`: the whole game (layout, styles and code).
- `assets/`: the 41 images the game uses, all supplied by the team.
- `video/`: 17 short rainforest clips cut from the team's footage (scenes, walking, bird and frog views, intro).
- `ui-frames/`: screenshots of every screen, for presentations.
- `reference-images/`: the 14 original full-resolution reference images supplied by the team.
