# Scramjet Flowpath Anatomy Jig

34-second schematic side elevation of a Mach 6 air-breathing scramjet. The shell lifts off, a shock train stays inside the isolator, struts inject fuel, the mixture lights, and the single-expansion ramp shows where force on the vehicle points.

Live plate: https://mizcausevic-dev.github.io/scramjet-anatomy-jig/

Repository: https://github.com/mizcausevic-dev/scramjet-anatomy-jig

## What this is

An interactive anatomy plate. Play, scrub, or jump the five chapters. The same frame always draws the same picture. 1,020 frames, 30 fps, 34.0 seconds.

## What this is not

A CFD result, a flight measurement, or a drawing of the X-43A. Shock angles, the wall-pressure shape, and the arrow field are compositional. `M∞ = 6` is the scenario, not a pitot reading. No thrust, specific impulse, recovery, or residence time is stated.

A different brief lives at https://github.com/mizcausevic-dev/scramjet-flowpath-explainer. Different palette, different stage list. Do not treat the two plates as one data set.

## Chapters

| Time | Frames | Plate |
| --- | --- | --- |
| 0.0–5.0 s | 0–150 | Ceramic panels leave on their surface normals. |
| 5.0–10.0 s | 151–300 | Shock-on-lip. Reflections stay downstream of the cowl lip. |
| 10.0–17.0 s | 301–510 | Three pylons. Fuel in the crossflow. One counter-rotating vortex pair. |
| 17.0–25.0 s | 511–750 | Autoignition in the strut wake. Core stays downstream. |
| 25.0–34.0 s | 751–1020 | SERN. Color arrows are velocity. Bone arrows are force. |

## Palette

Ceramic `#121316`. Titanium `#2E333D`. Mach violet `#7209B7` shocks. Shock yellow `#FFD000` compression core and fuel. Plasma `#F72585` ignition.

## Run

No build.

```bash
python3 -m http.server 8765
```

Open `http://127.0.0.1:8765/`. `?f=230&pause=1` parks on a frame. Space plays and pauses. `prefers-reduced-motion` parks on the nozzle plate until play.

GitHub Pages serves the `gh-pages` branch. `index.html` and `README.md` keep the names GitHub requires. `.nojekyll` skips Jekyll.

## Medium draft

`scramjet-flowpath-medium-Cursor.md` is the article draft. It is not a substitute for the plate, and it does not add performance numbers the plate refuses.

## Limits

No account, no form, no cookies, no analytics. Fonts are Space Grotesk and JetBrains Mono, SIL Open Font License, files and license text in `fonts/`.
