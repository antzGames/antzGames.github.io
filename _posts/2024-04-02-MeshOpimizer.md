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

The tool allows you to save each LOD as a separate GLTF file, or embed the LOD meta data in a separate file.  This meta data file can be used in libGDX using a easy to use LOD engine demo project.

![image](/assets/images/mesh.jpg)

## Quick Overview

Models are automatically optimized and LODs are generated on import. The default configuration is good in most cases, so just click EXPORT and you are done.
You need to click GENERATE if you change any LOD  settings.  Zoom camera in/out to see LOD transitions by using camera buttons or WASD or CURSOR keys.
Exporting LODs as separate GLTF files allows for your own custom LOD solution on any game engine.

If exporting using LOD meta data file, then you  can use the libGDX LOD example project as a template.  GitHub repository: [https://github.com/antzGames/Level_Of_Detail_Demo](https://github.com/antzGames/Level_Of_Detail_Demo)

## Features

- auto mesh optimize on import.
- auto LOD generation on import.
- exports LODs as separate GLTF files with one click.
- fully customizable LOD configuration:
    - number of LODs can be 3 to 8 levels.
    - configurable simplification factor.
    - configurable target error.
- can save LOD meta data into a separate file.
- fully preview all LODs before exporting.
- contains a built in animation player.
- based on the industry standard [meshoptimizer](https://meshoptimizer.org/) library.

You can download the tool at:

<iframe frameborder="0" src="https://itch.io/embed/2567177?border_width=2" width="554" height="169"><a href="https://antzgames.itch.io/libgdx-meshoptimizer">libGDX Mesh Optimizer Tool by Antz</a></iframe>

&nbsp;

Video explaining how to use the tool:

<iframe width="560" height="315" src="https://www.youtube.com/embed/-jZFwxxa6vs?si=cnrT6UBXQkZpxmjQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

&nbsp;

Only **gdx-gltf** supported **GLB** and **GLTF** files can be imported/exported.

