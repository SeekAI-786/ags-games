# AGS Games

Two browser games built as lightweight, self-contained HTML apps:

- **AI Arcade**: interactive games for learning supervised, unsupervised, and reinforcement learning.
- **The Clue Line**: a puzzle-based detective adventure.

## Run locally

Open `index.html` in a browser, or serve the folder with any static web server:

```bash
npx serve .
```

## Deploy

This repository has no build step. Import it into Vercel as a static project; Vercel will serve `index.html` at the root and the two games at their own `.html` paths.