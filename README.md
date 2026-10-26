# From-Seed-To-Tree
An interactive 2D animation built with C++ and OpenGL, illustrating the growth of an apple tree, with animated character, rain, dialogue, and sound effects.

## About the Project
The project tells a simple story about a character planting a seed and watching it grow into an apple tree. Through four scenes, the animation illustrates plant growth, rainy weather, and the appearance of apples.

## Features

- **2D Graphics:** Drawing characters, trees, clouds, the sun, and other objects using OpenGL.
- **Four Scenes:** Moving between different stages of the story.
- **Animated Sun:** Rotating sun rays.
- **Moving Clouds:** Clouds move across the sky.
- **Rain Animation:** Animated rain in the rainy scene.
- **Growing Tree:** Different stages of tree growth.
- **Falling Apple:** An apple falls when triggered by the user.
- **Character Animation:** A character walks toward the tree.
- **Textured House:** A house with textured walls and a roof.
- **Dialogue Box:** Displays story-related text in each scene.
- **Sound Effect:** Rain sound during the rainy scene.
- **Keyboard Interaction:** Users control scene transitions and animations.

## Technologies Used

- C++
- OpenGL
- GLUT / FreeGLUT
- Visual Studio
- Windows Multimedia API (`PlaySound`)
- BMP Textures

## Keyboard Controls

| Key | Action |
|---|---|
| `N` | Move to the next scene |
| `R` | Switch to the final scene |
| `W` | Start the character's walking animation |
| `F` | Trigger the falling apple in the final scene |

## Story Scenes

1. **Planting:** The story begins with the character and the seed.
2. **Rain:** Rain appears to represent the conditions that help the plant grow.
3. **Growth:** The tree grows larger.
4. **Fruits:** The mature tree produces apples, and the character can approach it.

## How to Run

1. Open the project in Visual Studio.
2. Configure OpenGL and FreeGLUT.
3. Ensure the required texture files are available:
   - `Brick.bmp`
   - `roof.bmp`
4. Ensure `Rain.wav` is available in the program's working directory.
5. Build and run the project.

**Note:** The sound feature uses the Windows Multimedia API and is enabled only on Windows.

## Project Objective

The objective is to apply fundamental computer graphics concepts, including 2D drawing, geometric transformations, animation, texture mapping, blending, and keyboard interaction.

## Project Information

**Course:** Computer Graphics

**Project:** Seasons of Growth

---

*Created as a Computer Graphics course project.*
