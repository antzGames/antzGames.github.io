---
title: "Godot Endless Ocean with Buoyancy"
date: 2026-09-21T15:34:30-04:00
categories:
  - Godot
  - demo
tags:
  - shader
  - 3D
header:
  teaser: /assets/images/endless_waves0.gif
---

![image](/assets/images/endless_waves1.png)

# Play in your browser:
<iframe frameborder="0" src="https://itch.io/embed/5017421?border_width=2&amp;dark=true" width="554" height="169"><a href="https://antzgames.itch.io/godot-endless-waves">Godot Endless Waves by Antz</a></iframe>

# YouTube Video:

<iframe width="560" height="315" src="https://www.youtube.com/embed/feZR6hQi5VI?si=HZtN-p_1ULhcALEK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
&nbsp;

# Features in this demo:
- Supports ALL RENDERES.
- Land collisions will sink ship.
- CPU based buoyancy calculation, with dampening and smoothing.
- 7 x 7 = 49 tiled Gerstner waves used to simulate endless oceans.
- Persisting Jacobian foam.
- Persisting ship intersection foam.
- Land will continuously spawn.
- Minimap showing active water tiles and land tile positions.
- Wind direction change affects sails and flags.

# Buttons and Controls:
- Switch Camera: North, East, South, West and Deck views.  SPACEBAR will also do switch.
- Wind +-: Change wind strength.
- Port / Starboard: Change ship direction.
- Wrench: Switch to ultra low resolution setting for mobile.
- Star: Opens YouTube video explaining solution.
- FullScreen: Forces fullscreen on the browser.

# Limitations:
- Intersection foam has a few bugs.
- You can still detect tile swaps in the distance if you look closely.
- Tiled waves pattern apparent when you zoom out.
- Only ship hatch has stencil.
- Works well on desktop GPUs.
- Will struggle on Mobile or older hadrware, make sure you click the WRENCH icon to switch to ultra low resolution mode.
