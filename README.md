# Terraria Valentine

A small pixel-style, Valentine-themed endless runner built with plain HTML5 Canvas and JavaScript.

## Quick Links

- Play now: `https://shadeekshap.github.io/VDay-Public/`

## Play Online (Recommended)

Play here: `https://shadeekshap.github.io/VDay-Public/`

## Game Description

`Terraria Valentine` is a fast arcade game where you protect your valentine while collecting heart gems.

- Collect hearts while avoiding or defeating enemies.
- Survive until the heart meter is full.
- Trigger a short victory cutscene when you win.
- On mobile, you can open your Messages app with a pre-filled Valentine message.

## How To Play

### Goal

Fill the heart meter by collecting **20 hearts**.

### Controls

- **Jump:** `Space`, `W`, or `Up Arrow`
- **Attack:** `X` or mouse click
- **Start / Restart:** `Space` (desktop) or tap (mobile)

### Enemies

As you collect more hearts, new enemy types appear (slimes first, then bats, then zombies).  
Use attacks and timing to survive while the game speed increases.

## Run The Game Locally

This project has no build step and no dependencies.

### Option 1: Open Directly

1. Open `index.html` in your browser.
2. Play immediately.

### Option 2: Run a Local Server (recommended)

From the project folder, run:

```bash
python3 -m http.server 8000
```

Then open:

`http://localhost:8000`

## Mobile Notes

- Mobile on-screen **JUMP** and **ATTACK** buttons appear automatically on touch devices.
- The “Send a Valentine Message” button uses an `sms:` link and works best on phones with a messaging app.

## Project Structure

- `index.html` - Complete game (HTML, CSS, and JavaScript in one file)

## Tech Stack

- HTML5 Canvas
- Vanilla JavaScript
- CSS

