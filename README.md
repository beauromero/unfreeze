# Unfreeze

Interval timer PWA for stretching routines.

Live at: https://beauromero.github.io/unfreeze

## What it does

- Guides you through a timed sequence of stretches with hold/rest intervals
- Works offline and installs to your phone's home screen (PWA with service worker)
- One-thumb, glanceable UI designed for use mid-stretch

## Stack

Vanilla HTML/CSS/JS, no build step. Service worker + web app manifest for offline/install.

## Run it locally

```sh
git clone https://github.com/beauromero/unfreeze.git
cd unfreeze
python3 -m http.server 8000
```

Open http://localhost:8000.

## Install on iPhone

1. Open the live URL in Safari.
2. Tap the Share button, then **Add to Home Screen**.
3. Launch it from the home screen — it runs fullscreen and works offline.
