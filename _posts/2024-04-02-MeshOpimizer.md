---
title: "GLTF Level of Detail Generator"
date: 2024-04-02T15:34:30-04:00
categories:
   - Tools and Plugins
tags:
  - LoD
  - optimization
  - 3D
header:
  teaser: /assets/images/mesh.jpg
---
I developed a tool that allows easy creation of LODs from your models with only a few clicks.

The tool allows you to save each LOD as a separate GLTF files.

![image](/assets/images/mesh.jpg)
&nbsp;
![image](/assets/images/mesh_gif.gif)

## Quick Overview

Models are automatically optimized and LODs are generated on import. The default configuration is good in most cases, so just click EXPORT and you are done.
You need to click RE-GENERATE if you change any LOD  settings. Exporting LODs as separate GLTF files allows for your own custom LOD solution on any game engine.

## Features

- auto mesh optimize on import.
- auto LOD generation on import.
- exports LODs as separate GLTF files with one click.
- fully customizable LOD configuration:
    - number of LODs can be 3 to 8 levels.
    - configurable simplification factor.
    - configurable target error.
- fully preview all LODs before exporting.
- based on the industry standard [meshoptimizer](https://meshoptimizer.org/) library (v0.23).

You can download the tool at:

<iframe frameborder="0" src="https://itch.io/embed/2567177?border_width=2" width="554" height="169"><a href="https://antzgames.itch.io/meshoptimizer">GLTF Mesh Optimizer Tool by Antz</a></iframe>

&nbsp;

Video explaining how to use the tool:

<iframe width="560" height="315" src="https://www.youtube.com/embed/Z39_deTzp9A?si=Y6kYD5seBMGobyxK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>