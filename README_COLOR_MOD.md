# Color Asteroids Modification

This version modifies the provided Panda3D asteroids project so the player can change ship color and shoot color-specific bullets.

## Controls

- Left Arrow: turn left
- Right Arrow: turn right
- Up Arrow: accelerate
- Space: fire
- 1: change ship to red
- 2: change ship to green
- 3: change ship to blue
- ESC: quit

## Color rules

- The player starts red.
- Pressing 1, 2, or 3 changes the ship to red, green, or blue.
- Every asteroid receives a random color when spawned.
- Any asteroid color can still destroy the player.
- A bullet can only destroy an asteroid if the bullet color matches the asteroid color.
- Bullets inherit the player's color at the moment they are fired.
- A bullet keeps its original color even if the player changes color after shooting.

## Bullet behavior

- Red bullets move faster.
- Green bullets fire in three directions.
- Blue bullets pierce through matching asteroids instead of disappearing after one hit.
