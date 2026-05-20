# 💊 Valley of the Dolls — Trivia Game

> *"You've got to climb to the top of Mount Everest to reach the Valley of the Dolls."*

A campy, over-the-top browser trivia game covering Jacqueline Susann's iconic 1966 novel and the 1967 film adaptation.

## Features

- **80-question library** — randomly draws 20 per game, so every play is different
- **6 categories:** 📖 The Book · 🎬 The Film · ⭐ Casting Drama · 🎭 Behind the Scenes · 👑 Legacy & Camp · 💬 Famous Lines
- YouTube & Spotify links woven into questions and feedback
- Pill-shaped lives, streak counter, score tracking
- **Shareable results card** — generates a downloadable PNG share image with your score, plus one-click sharing to X, Facebook, and clipboard
- Pill emoji favicon (purple & pink, naturally)
- Zero dependencies — pure HTML, CSS, and vanilla JS

## Deployment

### GitHub Pages (recommended)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Your game will be live at `https://[your-username].github.io/[repo-name]/`

### Vercel

1. Import the repo in [vercel.com](https://vercel.com)
2. Framework preset: **Other**
3. Output directory: leave blank (root)
4. Deploy — done

## Files

```
index.html    ← the entire game (self-contained)
README.md     ← this file
```

## Tech

Single-file HTML — no build step, no dependencies, no framework.  
Fonts loaded from Google Fonts (Abril Fatface, DM Serif Display, Nunito).  
Share card generated via HTML5 Canvas API.

---

*Based on the novel by Jacqueline Susann (1966) and the film directed by Mark Robson (1967).*
