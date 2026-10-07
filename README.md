# AGS Games

Three browser games built as lightweight, self-contained HTML apps by Align Global Solution:

- **AI Arcade** (`learn-ai-games.html`): interactive games for learning supervised, unsupervised, and reinforcement learning.
- **The Clue Line** (`clue-line-app.html`): a puzzle-based detective adventure for ages 5–10 and 10–15. Pick one mission, solve it (tap Hint and answer a quick sum if you get stuck), and get a score.
- **Math & Science Lab** (`math-science-lab.html`): eight stations (4 math, 4 science) with six quick challenges each, a 2-minute round, a lab report and a "Where is AI?" card. Grades 2–3 and 4–6.

Scores for The Clue Line and the Math & Science Lab are kept in the browser's localStorage on the device (separate leaderboards).

## Run locally

Open `index.html` in a browser, or serve the folder with any static web server:

```bash
npx serve .
```

## Deploy

This repository has no build step. Import it into Vercel as a static project; Vercel will serve `index.html` at the root and each game at its own `.html` path.

## Notes for editing

- Math & Science Lab: all on-screen text and question wording are in the `STR` object at the top of the script, so a translation (for example Urdu) only needs that object changed.
- "Read to me" buttons use the browser's speech synthesis and only speak after a tap.
