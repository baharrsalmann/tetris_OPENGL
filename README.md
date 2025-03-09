
# TetrisGL  

### 3D Rendering with OpenGL  

This project is a 3D Tetris-style game built using OpenGL and GLSL shaders, written in C++. The goal is to implement a simple 3D game that resembles classic Tetris while utilizing modern graphics programming techniques.

## Features  
- **3D Game Mechanics**: A falling 3×3 cube that can be moved left and right.  
- **Grid-based Board**: A 9×9 game board with clear grid lines.  
- **Camera Rotation**: Smooth rotation of the game area.  
- **Lighting & Shading**: Uses ambient, diffuse, and Blinn-Phong shading.  
- **Collision Detection**: Blocks stack properly without intersection.  
- **Score System**: Tracks points based on collapsed rows.  
- **Game Over Condition**: The game ends when a block cannot be placed.  

## Controls  
- `A` - Move left  
- `D` - Move right  
- `S` - Speed up falling  
- `W` - Slow down falling  
- `H` - Rotate view left  
- `K` - Rotate view right  

## Technologies Used  
- **C++** for core game logic  
- **OpenGL** for rendering  
- **GLFW** for window management  
- **GLEW** for OpenGL extensions  
- **GLM** for mathematical operations  

## How to Run  
1. Compile the code using `make`.  
2. Run the executable `./tetrisGL`.  
