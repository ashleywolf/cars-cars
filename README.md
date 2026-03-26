# Cars Cars 🚗

A webcam game for toddlers (and anyone who thinks chomping cars is funny).

Cars drive across a city street. Open your mouth to catch them. That's it. That's the game.

## Car Types

- **Green hatchback** -- fast, common, 1 point
- **Rainbow car** -- animated gradient paint job, 2 points
- **Tesla** -- sleek blue-accent sedan, 3 points
- **Cybertruck** -- angular steel wedge, rare, 5 points

## How It Works

Uses MediaPipe FaceLandmarker to track your mouth in real-time. When your jaw opens wide enough and a car is nearby, you "chomp" it. Supports up to 4 faces simultaneously so multiple kids can play at once.

## Toddler-Friendly Tuning

Big cars, slow speeds, 8 lives, forgiving catch radius, gentle difficulty ramp. The game runs for 120 seconds per round. Designed so a 2-year-old can actually catch things.

## Play It

**[Play Cars Cars](https://ashleywolf.github.io/cars-cars/)**

Best in Chrome. Needs a webcam.

## Tech

Single HTML file. Canvas 2D rendering. MediaPipe FaceLandmarker via CDN. Web Audio API for procedural sound effects (honks, vrooms, screeches). No build tools, no dependencies, no npm.

Part of the [Browser Party Games](https://github.com/ashleywolf/webcam-games) collection.
