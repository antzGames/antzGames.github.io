---
title: "Marble Marcher"
date: 2023-10-14T15:34:30-04:00
categories:
  - libGDX
tags:
  - 3D
  - ray-marching
  - fractals
  - shaders
---

Marble Marcher is entirely ray-marched (similar to ray-tracing) in real time and is played on the surface of evolving fractals.  The goal is to get your marble to the goal as quickly as possible.  There are 24 unique levels to master.

Best times are stored via the Game Jolt API.  

## Ported to Java utilizing libGDX

The C++ code has been migrated to Java using the libGDX game framework.  All linear algebra math converted to libGDX's math classes (i.e. no more Eigen linear algebra library needed).  This code base can support iOS, Android, HTML and any desktop (Linux/Windows).

Levels unlocks are saved (persisted) via local browser storage.

<iframe frameborder="0" src="https://itch.io/embed/2311404?border_width=3" width="556" height="171"><a href="https://antzgames.itch.io/marble-marcher-in-a-browser">Marble Marcher: Browser Edition by Antz</a></iframe>

![AqPZlZ](/assets/images/mm1.png)

![fRIWoJ](/assets/images/mm2.png)

![RznvxS](/assets/images/mm3.png)

![6HNEsH](/assets/images/mm4.png)




