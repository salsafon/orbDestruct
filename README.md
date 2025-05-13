# orbDestruct

My first Unreal Engine project – a physics sandbox where you launch metal spheres to mess with the environment.

## Overview

**orbDestruct** is a simple physics-based prototype built with Unreal Engine 5.  
There are no weapons or characters — you control a floating camera and launch metal orbs by looking at any direction. These orbs push and scatter objects around using physics.

This project was created as my first hands-on attempt to learn Unreal Engine's basics: blueprint logic, physics interactions, input systems, and level design.



## Features

- Camera-based metal sphere launching
- Interactive objects that respond to hits
- Blueprint-only logic (no C++ code)
- Minimalist sandbox setup



## Project Structure

- `Content/` – All assets, blueprints, materials, etc.
- `Config/` – Game and engine settings
- `WreckIt.uproject` – Main project file

Unnecessary folders like `Saved/`, `Intermediate/`, and are excluded via `.gitignore`.



## How to Play

1. Clone the repo:
   ```bash
   git clone https://github.com/salsafon/orbDestruct.git
2. Open WreckIt.uproject with Unreal Engine 5
3. Click the "Play" button in the editor
4. Move around with WASD, look with the mouse, and shoot spheres by pressing space


## Goal

There is no win condition — it's just for testing and fun. Try launching orbs at stacks of objects and watch them fly!

## Learning Purpose

This project helped me understand:

- How to create a basic UE5 project from scratch
- Using blueprint scripting for player input and physics
- Setting up a simple scene with movable objects
- Working with .gitignore and pushing to GitHub


