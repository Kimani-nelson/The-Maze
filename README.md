# SDL2 Raycasting Game

Author: Nelson Kimani

## Project Overview

The goal of this project is to create a 3D game using raycasting with SDL2. The game will involve drawing walls, handling player movement and collisions, implementing a parser for map files, and adding various features like textures, weapons, enemies, rain, and more.

## Requirements

### General

- All files compiled on Ubuntu 14.04 LTS, using gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4.
- Use gcc flags: -Wall -Werror -Wextra -pedantic.
- Functions must be commented.
- Functions should be maximum 40 lines long, 80 columns wide.
- No more than 5 functions per file.

### Betty

- Entire repository checked using Betty.
- Do not push object files (.o), temporary files (*~), or any unused source files.

### Organization

- Maintain clear organization in the repository (e.g., src for sources, inc for headers).
- Use SDL2 for development.

## Tasks

1. **Walls!**
   - Create an SDL2 window.
   - Use raycasting to draw walls on the window.
   - Implement a way to change the camera angle in the code.
   - Walls' color must differ from ground/ceiling.

2. **Orientation**
   - Draw walls facing NORTH/SOUTH in a different color from walls facing EAST/WEST.

3. **Rotation**
   - Provide a way to rotate the camera during execution (e.g., arrow keys or mouse).

4. **Move**
   - Implement player movement during execution (e.g., w,a,s,d keys).

5. **Ouch!**
   - Handle player collisions with walls.
   - Allow the player to slide on walls.

6. **Parser**
   - Implement a parser to get the map from a file.
   - Define map standards (e.g., wall character, empty character, file extension).
   - Use a parameter for the map file path.

7. **Draw the Map**
   - Draw the map on the window.
   - Provide a way to enable/disable it during execution.
   - Include the player's line of sight in the map.

8. **Textures**
   - Add textures to walls.

9. **Multi Task!**
   - Handle multiple directions and rotations simultaneously.

10. **Ground Textures**
    - Add textures on the ground and/or ceiling.

11. **Weapons**
    - Add weapon textures.

12. **Enemies**
    - Introduce enemies.

13. **Make it Rain**
    - Add rain with the ability to start/stop it with a key.

14. **Extra Option**
    - Get creative with additional features (shadows, special lighting, etc.).

## Coding Style + Documentation

- Check if the code fits Holberton School coding style.
- Ensure the code is well-documented following Holberton School documentation format.

## Tips and Resources

- [SDL2 Get Started.pdf](link-to-sdl2-get-started.pdf)
- [SDL2 Tutorials](link-to-sdl2-tutorials)
- Be careful with online tutorials; use SDL2, not SDL-1.2.
- RAYCASTING!!! [Alternative Raycasting Tutorial](link-to-alternative-raycasting-tutorial)

## Important Notes

- Install SDL2 and follow the SDL2 tutorials.
- No forbidden functions; use any system call and/or standard library function.
- Utilize all functions provided by SDL2.

Have fun developing your SDL2 raycasting game!
