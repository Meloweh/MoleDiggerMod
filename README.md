# Baba is You: Mole Digger Mod (2019)

This modification allows the player to move through walls.

Baba Is You is a puzzle game that links instruction blocks that trigger effects in the level.
Similar to the "LISA Infinite Magazines" project, the target address for testing the
collision with a wall is determined dynamically by register comparisons.
The player moves to the left in the video, since the desired register state is only present during a
during a movement of the player.

Once the address has been found, the collision mask of an object in front of the
player can be easily teleported to a less disturbing position.

## Video

https://github.com/Meloweh/MoleDiggerMod/assets/49780209/32c89bfd-8de7-486e-8f15-f9ff8272a703

## Languages
- Lua
- Assembly
