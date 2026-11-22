# Before the Sun Sets

A first-person, photographic time-loop game. Notice clues, borrow an animal's senses, and guide the pangolin to the refuge before sunset.

## Publish on GitHub Pages
1. Create a new public repository. GitHub's website takes up to 100 files per upload, so upload in three goes: (1) `index.html`, `assets`, `sprites` and `audio`; (2) `video`; (3) optionally `ui-frames`, `reference-images` and this README.
2. Go to Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, and save.
3. After about a minute, GitHub shows the game's link at the top of the Pages settings.

To test on your own computer, run a small local server in this folder (for example `python3 -m http.server`) and open http://localhost:8000. Opening the file directly also works in most browsers.

## Controls
W or Up: walk forward to the next place. A/D or Left/Right: turn to face another direction. S or Down: turn around. Mouse: look around (click the view to lock the mouse). E: inspect or talk. 1 to 4, P, Q, Tab or the mouse wheel: switch sense (Human, Bird, Frog, Leopard). M: map. J: journal. I: info. T (hold): let time pass. N: skip to the next day. C: choose any day and time of day. [ and ]: move the clock one hour. Esc: pause.

## Files
- `index.html`: the whole game (layout, styles and code).
- `assets/`: the 41 images the game uses, all supplied by the team.
- `video/`: 40 short rainforest clips cut from the team's footage (every place seen in four directions, walking, bird and frog views, intro).
- `audio/`: rainforest ambience and running water taken from the team's footage.
- `assets/inst_*`: installation references from the team's mood board, shown on the entrance screen.
- `sprites/`: cut-outs of the pangolin, tortoise, hornbill and frog placed in the forest.
- `ui-frames/`: screenshots of every screen, for presentations.
- `reference-images/`: the 14 original full-resolution reference images supplied by the team.
