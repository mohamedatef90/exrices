# Exrices

A single-page, Arabic (right-to-left) exercise guide: a knee rehabilitation and strengthening program plus fitness and gym training plans, with an exercise card and image for each movement.

## What is in the page

The page (`index.html`, title "برنامج الركبة – الاستشفاء والتقوية") has five tabs:

- **قبل اللعب** (Before playing)
- **بعد اللعب** (After playing)
- **تمارين يومية** (Daily exercises)
- **تمارين اللياقة** (Fitness exercises)
- **برنامج الجيم** (Gym program), with a day selector for a seven-day plan from Saturday to Friday (chest, back, legs, shoulders, arms, cardio, rest)

Exercise images are loaded from an external site (`gymvisual.com`), so images need an internet connection.

## Tech

A single self-contained HTML file with inline CSS and JavaScript: no build step, no dependencies. The styling is a dark glassmorphism theme with CSS custom properties and a responsive grid; tab switching is done with small `show` and `showDay` functions. Web fonts load from Google Fonts.

## Running

Open `index.html` in a browser; no server is required.

## Files

- `index.html`: the whole app
- `CLAUDE.md`: notes for AI coding assistants
