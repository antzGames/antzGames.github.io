---
title: "libGDX MeshOptimizer Tool"
date: 2024-04-02T15:34:30-04:00
categories:
  - libGDX
  - Tools and Plugins
tags:
  - LoD
  - optimization
  - 3D
header:
  teaser: /assets/images/mesh.png
---
I developed a tool to optimize your GLTF models for use in libGDX.  It uses the popular [MeshOptimizer](https://meshoptimizer.org/) library.  Simplification, mesh optimization and model import/export are feature complete.

![image](https://github.com/antzGames/antzGames.github.io/assets/10563814/5bfaa4e8-e1cf-463d-979c-f33f17d602a7)

You can download the tool at:

<iframe frameborder="0" src="https://itch.io/embed/2567177?border_width=2" width="554" height="169"><a href="https://antzgames.itch.io/libgdx-meshoptimizer">libGDX Mesh Optimizer Tool by Antz</a></iframe>

&nbsp;

Video explaining how to use the tool:

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ne-lEDXHhys?si=nkvDscbYduR06PPA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

&nbsp;

Only **gdx-gltf** supported **GLB** and **GLTF** files can be imported/exported.

Here is the supported pipeline:

* Indexing
* Simplification
* Vertex cache optimization
* Overdraw optimization
* Vertex fetch optimization

## Why is this important?
This will give the libGDX 3D community the ability to have Level of Detail (LoD) rendering and also provide improved frame per second (FPS) on their 3D games.

Initial testing has shown 10-50% rendering improvements on an un-simplified mesh that has been optimized.

The JNI interface to MeshOptimizer is provided via LWJGL.

The Java jar file can be run on Windows and Linux , but you need Java 11+ installed.

## User Interface

![download](https://github.com/antzGames/antzGames.github.io/assets/10563814/899beb29-f53e-4f01-ada5-3de13f08227f)

Here are the before and after optimization metrics:

![OOUfua](https://github.com/antzGames/antzGames.github.io/assets/10563814/4398f057-e7c2-41f3-a8f4-b9217046a39b)
