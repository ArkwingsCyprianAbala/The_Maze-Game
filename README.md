# The Maze

The Maze is a 3D game built using SDL and raycasting techniques. In this game, players navigate through a maze, turning left or right as desired. If a player hits a wall, they must change direction to continue. Here are the details:

The Maze was written in C using SDL2 library. Deveploment was performed using Ubuntu 24.04 - gcc (Ubuntu 11.3.0-1ubuntu1~22.04) 11.3.0

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Installation 
```sh
$ git clone https://github.com/ArkwingsCyprianAbala/The_Maze-Game.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```
## Contributing
Read the source files in the src folder and the header files in the inc folder.
Clone the repo and create a new branch:
git checkout -b name_of_new_branch

Add features, fix bugs, or refactor code.
Write/update tests if necessary.
Update the README.md if needed.
Open a Pull Request with a comprehensive description of changes.

## Author

- Arkwings Cyprian Abala (https://github.com/ArkwingsCyprianAbala)>
