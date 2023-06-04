# Baba is You: Mole Digger Mod (2019)

This modification allows the player to move through walls.

Baba Is You is a puzzle game that links instruction blocks that trigger effects in the level.
Similar to the "LISA Infinite Magazines" project, the target address for testing the
collision with a wall is determined dynamically by register comparisons.
The player moves to the right in the video, since the desired register state is only present during a
during a movement of the player.

Once the address has been found, the collision mask of an object in front of the
player can be easily teleported to a less disturbing position.

## Video

[![IMAGE ALT TEXT](http://img.youtube.com/vi/g1MOEgDb8bA/0.jpg)](http://www.youtube.com/watch?v=g1MOEgDb8bA "Baba Is You Mole Mod Dig through tiles")

## Languages
- Lua
- Assembly
