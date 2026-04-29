# PulseForge Training OS

Commercial-style exercise app built as a single-page web app with local persistence and PWA support.

## Main App

- Entry page: `index.html`
- Primary app: `commercial-exercise-app.html`
- Legacy tracker kept for reference: `gym-workout-checklist.html`

## Features

- Personalized onboarding with goal, experience, equipment, and preferred workout styles
- Smart weekly plan generation with progression notes
- Workout library with filters (type, level, equipment, duration, search)
- Live session mode with set completion tracking, workout clock, and rest timer
- Nutrition logging with macro targets, quick add, barcode lookup samples, fasting, and multi-day copy
- Recovery check-ins (sleep, soreness, stress) with readiness scoring
- Progress analytics: streaks, personal bests, history tables, and trend charts
- Challenge tracking for sessions, hydration, and consistency streaks
- Local community feed for accountability updates
- Export/import support (`JSON`, workout `CSV`)
- Installable app experience (`manifest.webmanifest` + `sw.js`)

## Run Locally

Open `index.html` directly, or serve this directory:

```bash
python3 -m http.server 8197
```

Then open:

`http://127.0.0.1:8197/`
