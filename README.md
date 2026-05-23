# Godot Digital Asset Collection Demo

## Overview

The **Godot Digital Asset Collection Demo** is a 2D interactive game-development portfolio project built with **Godot Engine** and **GDScript**.

This project demonstrates basic game-engine workflows, digital asset organization, scene setup, player movement, collectible object behavior, collision detection, UI scoring, and clean technical documentation.

The project was created to show hands-on experience with Godot and digital asset refinement workflows relevant to game development, AI training, and interactive content evaluation projects.

---

## Project Purpose

This project was designed as a professional portfolio piece for game-development and AI research opportunities that involve building, reviewing, organizing, and refining digital assets.

The goal is to demonstrate the ability to:

- Work inside a modern game engine
- Organize project files clearly
- Build a simple interactive scene
- Create and manage digital assets
- Write basic game logic using GDScript
- Document the project in a professional way
- Connect technical work to AI training and asset evaluation workflows

---

## Game Concept

The demo is a simple 2D asset collection game.

A player-controlled character moves around the screen and collects digital asset icons. Each collectible represents a digital asset. When the player touches a collectible, the item disappears and the score increases.

This simple interaction demonstrates core game-development concepts such as movement, collision detection, object interaction, and UI updates.

---

## Features

- 2D interactive scene built in Godot
- Player movement using keyboard controls
- Collectible digital asset objects
- Collision detection using `Area2D`
- Score tracking system
- UI label that updates during gameplay
- Organized asset folders
- Separated scripts for player, collectible, and game manager logic
- Clean GitHub documentation
- Screenshots folder for portfolio presentation

---

## Tools and Technologies

- **Godot Engine**
- **GDScript**
- **2D Scene Editor**
- **GitHub**
- **Git Version Control**

---

## Project Structure

```text
godot-digital-asset-collection-demo/
│
├── README.md
├── project.godot
│
├── assets/
│   ├── player/
│   ├── collectibles/
│   ├── backgrounds/
│   └── ui/
│
├── scenes/
│   ├── Main.tscn
│   ├── Player.tscn
│   └── Collectible.tscn
│
├── scripts/
│   ├── player.gd
│   ├── collectible.gd
│   └── game_manager.gd
│
└── screenshots/
    ├── main-scene.png
    └── gameplay.png
