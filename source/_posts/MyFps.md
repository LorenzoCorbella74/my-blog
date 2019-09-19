---
title: MyFps
date: 2019-09-19 11:19:37
categories: [Projects,Coding]
tags: [coding, game development,webapp]
thumbnail: /images/myFps.PNG
---
![coding1](/images/myFps.PNG)
My first attemp in the magic world of game development. MyFps is a 2D top down shooter, developed in ***Typescript*** in the summer of 2018 for learning the ***CANVAS API***. The game seeks to recreate the game mechanics of arena shooter like Quake 3 Arena, Unreal tournament, etc. Follow the [link](https://lorenzocorbella74.github.io/test-canvas-game/) to play the game or check the [code](https://github.com/LorenzoCorbella74/test-canvas-game) on Github to see how it works.

## Main Features
- scrolling map built with tiles of different types (solid, lava, toxic water)
- camera following different entities (player, bots)
- collision system for all entities
- debug mode (+ god mode, camera cycle for bots)
- spawn mechanism with animation
- particles (debris, blood) and explosion
- powerups system with different respawn times + counters
- different weapons with different effects
- bots AI
    - navigation with A* based on waypoints and powerups, ammo, weapons
    - brain with Finite state machine, line of sight, target estimation aim, use of different weapons
- UI MESSAGES
- different game modes (deathmatch, team deathmach)
