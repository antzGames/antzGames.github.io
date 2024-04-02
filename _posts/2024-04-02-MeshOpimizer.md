---
layout: post
title: "libGDX MeshOptimizer Tool"
description: "Opitimize your GLTF 3D models with my tool"
tags: Java-Port
---

# libGDX MeshOptimizer Tool

![image](https://github.com/antzGames/antzGames.github.io/assets/10563814/5bfaa4e8-e1cf-463d-979c-f33f17d602a7)

<iframe frameborder="0" src="https://itch.io/embed/2567177?border_width=2" width="554" height="169"><a href="https://antzgames.itch.io/libgdx-meshoptimizer">libGDX Mesh Optimizer Tool by Antz</a></iframe>

This is a tool to optimize your GLTF models for use in libGDX using the MeshOptimizer library.

Simplification, mesh optimization and model import/export are feature complete.

Only gdx-gltf supported GLB and GLTF files can be imported/exported.

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
