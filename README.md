# B/W

**B/W** is a 2D puzzle-platformer built around one central idea: color changes the rules of the world. Switch the player between black and white, move through matching-color objects, stand on contrasting platforms, and combine precise movement with color-based puzzle solving to reach each level's green exit.

## Play the Game

[Play the Gold WebGL build](https://zzxxjj1.github.io/BW_Gold_Final/)

The game runs in a modern desktop browser with WebGL 2 support. For the best experience, play with a keyboard and allow the game a moment to load.

## Game Overview

Each level asks the player to explore a monochrome environment, avoid hazards, manage limited health, defeat or evade enemies, and discover a route to the endpoint. Platforms, barriers, enemies, and moving blocks respond differently to the player's current color, turning color switching into both a traversal tool and a puzzle mechanic.

The main gameplay loop is:

1. Explore the level and identify color-based obstacles.
2. Switch between black and white to change which surfaces are solid or passable.
3. Combine movement, jumping, combat, and environmental recoloring to open a route.
4. Reach the green endpoint to complete the level.

Falling out of the level or losing all health restarts the current stage.

## Core Mechanics

- **Color switching:** Change the player between black and white to interact with platforms, barriers, hidden routes, and enemies.
- **Platforming:** Run, jump, and time mid-air color changes to cross gaps and move through color blocks.
- **Color-based enemies:** Use the correct color state to avoid or defeat black and white enemies; gray enemies remain dangerous in either state.
- **Color gun:** Fire black or white pigment to recolor selected environmental objects and create a path forward.
- **Block machines:** Navigate continuously generated moving blocks, including gray blocks that push the player back.

## Levels

- **Level 01 - Tutorial:** Learn movement, jumping, color switching, and how to combine jumping with a mid-air switch.
- **Level 02:** Apply the core mechanic against enemies, block machines, and hidden routes.
- **Level 03:** Use the color gun to solve more involved environmental puzzles.
- **Bonus Level:** Move through color blocks, avoid obstacles, and reach the far end of a faster arcade-style challenge.

## Controls

| Action | Keys |
| --- | --- |
| Move | `A` / `D` or Left / Right Arrow |
| Jump | `Space`, `W`, or Up Arrow |
| Switch color | `K` or `S` |
| Shoot color gun | `J` or `F` |

## Design

The visual direction uses a restrained black, white, and gray palette so that color is never only decoration: it communicates whether an object is visible, solid, passable, or dangerous. The minimalist presentation keeps the player's attention on spatial reasoning, timing, and the relationship between the character and the environment.

For the full concept, level sketches, UI flow, development timeline, and playtest notes, see the [Game Design Document](./B_W%20GDD.pdf).

## Technical Details

- Engine: Unity `2022.3.17f1`
- Genre: 2D puzzle-platformer
- Platform: WebGL / desktop browser
- Build: Gold release

This repository contains the final WebGL build and the project's Game Design Document.

## Team

- [Hao Feng](https://github.com/Matt23-star) - Team Captain, Physics, UI
- [Xuejin Zheng](https://github.com/zzxxjj1) - Product Manager, Physics, UI
- [Qijun He](https://github.com/qijunhe) - Stenographer, Physics, UI
