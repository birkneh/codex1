# Gym Workout Checklist

Simple HTML workout tracker for a 3-day full-gym program.

## Features

- 3-day split that trains major muscle groups 2x/week
- Built-in protein target calculator
- Per-exercise tracking for weights, reps, pain score, and notes
- Follow-along mode with one exercise at a time
- Rest timer with start/pause/reset and +15s control
- Auto-save using browser localStorage
- CSV export
- Video link per exercise
- Installable web-app style experience (manifest + service worker)

## Run Locally

Open `gym-workout-checklist.html` directly in your browser.

## Use on Phone (same Wi-Fi)

Serve the folder from your computer:

```bash
python3 -m http.server 8197
```

Then open on phone:

`http://<your-computer-ip>:8197/gym-workout-checklist.html`

## Install on iPhone

1. Open the app in Safari.
2. Tap Share.
3. Tap `Add to Home Screen`.
4. Launch it from the home screen for full-screen follow-along mode.
