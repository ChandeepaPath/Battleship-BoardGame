# Battleship-BoardGame

## 🎮 Game Description

This project recreates Battleship with drag-and-drop interaction, multiplayer support, and a clean top-down view for each player. Players place ships, take turns, and try to sink each other’s fleet!

## Preview

![Game Preview](Game-Workflow.jpg)

## 🔹 Main Stages

- Main Menu
  - Options to host or join a multiplayer session.
  - Starts the top-down level once connected.
  
- Entity Placement
  - Each player drags their ships onto the 3D board.
  - Rotation allowed.
  - Confirm/Ready button once all ships are placed.
  
- Gameplay Loop
  - Players take turns selecting their opponent’s board tiles.
  - Server replicates result (hit or miss).
  - The game ends when one player loses all ships.
  
- Game Over
  - Results shown with replay/quit options.
