---
title: "Underworld Survival"
date: 2024-03-28T15:34:30-04:00
categories:
  - libGDX
  - GameJams
tags:
  - 3D
  - instancing
---
_Help the mage survive the Underworld._  This is a simple game, but its using instancing to draw hundreds of  models on the screen.  Each individual instance has its location, rotation and scale controlled, while your GPU is doing very little work to render the scene.

![dl1](/assets/images/uw1.png)

![dl2](/assets/images/uw2.gif)

![dl2](/assets/images/uw2.gif)

The first four levels are time trials, so your fastest time is saved.

**Level 5** is survival mode.  Try to survive as long as possible.

You get a free weapon upgrade on **Level 3**.

## Controls

| **A** and **S** Keys | Rotate Left/Right |
| **LEFT** and **RIGHT** Cursor Keys | 	Rotate Left/Right | 
| **CTRL** Key | Slow down rotation | 
| Right Mouse Button | Pause Menu
| **G** Key	Shadow quality toggle. | Reduce shadow quality significantly, but will boost your FPS.  Only use if you are below 60 FPS.  

## High Scores
Scores are saved via GameJolt API.  If you have a GameJolt userid, you can log in with your credentials, and earn trophies.  

If you do not have a GameJolt userid, its ok, just login as **GUEST** and select a username. The game will remember it, so you only need to do this once.

Your best scores are also saved to local browser storage. 

You can clear out your guest name and local scores by pressing the **L** KEY from the main menu.

## Instancing
This is a simple game, but its using instancing to draw 300 (plus 300 hidden) models on the screen.  Each individual instance has its location, rotation and scale controlled, while your GPU is doing very little work to render the scene.

Even on an old 2017 laptop with integrated graphics, I manage to get 27 FPS.

Newer hardware should perform much better.

If you have low FPS type the **G** Key at any time to reduce the shadow quality.  This should boost your FPS.

Note: Your PC/Laptop needs to support OpenGL 4.1.

## Credits
Music by: PettyTheft: SoundCloud: [https://soundcloud.com/ppettytheftt](https://soundcloud.com/ppettytheftt)

3D models by KayKit: [https://kaylousberg.itch.io/kaykit-adventurers](https://kaylousberg.itch.io/kaykit-adventurers)

libGDX GameJolt API: [https://github.com/raeleus/game-jolt-api](https://github.com/raeleus/game-jolt-api)

## Play online

You can play online:

<iframe frameborder="0" src="https://itch.io/embed/2602372?border_width=2" width="554" height="169"><a href="https://antzgames.itch.io/underworld-survival">Underworld Survival by Antz</a></iframe>

