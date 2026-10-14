# NEO-VERIDIA 2099

A single-file interactive cyberpunk flight experience set in a procedural megacity of the future.

This project renders a massive, infinite cityscape with a stylized neon HUD, shader-driven atmosphere, moving traffic lanes, wet pavement reflections, and free-flight controls in a browser.

## Overview

`neo_veridia_2099_infinite_procedural_cyberpunk_city.html` is a standalone HTML scene built with:

- HTML/CSS/JavaScript
- Tailwind CSS via CDN
- Three.js via CDN
- Custom GLSL shaders for city geometry, atmosphere, rain, wet streets, and traffic

The experience presents:

- an endless procedural skyline with layered megastructure blocks
- animated traffic flow across elevated lanes and street grids
- atmospheric fog, bloom, and mood lighting
- a cyberpunk flight UI with telemetry and control panels
- multiple visual themes and live environment sliders

## Features

- Infinite procedural city generation
- Dynamic sky, haze, and neon lighting system
- Rain, reflections, and wet asphalt visuals
- Air-traffic lanes and moving light streaks
- Free-flight camera movement with keyboard + mouse controls
- HUD overlays and shader deck settings
- Multiple color themes and live sliders for visual tuning

## Run it locally

Because this is a self-contained browser demo, you can run it in either of these ways:

1. Open the HTML file directly in a browser
   - Double-click `neo_veridia_2099_infinite_procedural_cyberpunk_city.html`
   - or open it through your browser's file menu

2. Serve it with a local web server (recommended)

```bash
cd C:\dev\Neo-Veridia-2099
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/neo_veridia_2099_infinite_procedural_cyberpunk_city.html
```

## Controls

- `W/A/S/D` — thrust / movement
- `Mouse` — pitch and yaw
- `Shift` — afterburner boost
- `Space / C` — altitude control
- `Q / E` — roll
- `P` — autopilot
- `H` — toggle shader deck
- Click the on-screen button to engage free-flight mode

## Files

- `neo_veridia_2099_infinite_procedural_cyberpunk_city.html` — main interactive experience
- `README.md` — project overview and usage instructions

## Notes

- The project loads external CDN resources for Tailwind CSS and Three.js, so internet access is required for full rendering.
- This is a visual prototype / interactive art demo rather than a production app or game engine project.
- Performance depends on browser capabilities and GPU support.

## License

This project does not currently include a formal license file. If you are publishing or distributing it, add an appropriate license before sharing externally.
