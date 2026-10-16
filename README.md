# Toss And Blend
*A Scratch project created for the CS50x course.*

## Description
This is an interactive arcade game where the player must use a mouse-controlled paddle to juggle falling fruits and guide them into a blender. The game features progressive difficulty, full collision physics with the table and blender, and distinct game states including a title screen, game over screen, and victory screen. 


## Download & Play

**[Download Toss-and-Blend v1.0](https://github.com/datwave999/Toss-and-blend/releases/latest)**

### Available Versions
| Platform | File | Instructions |
|---|---|---|
| Windows | `TossAndBlend_v1.0_Windows.zip` | Extract and launch the game |
| macOS | `TossAndBlend_v1.0_MacOS.zip` | Extract and launch the app |
| Browser | `TossAndBlend_v1.0.html` | Download and open in a web browser |

## Objective
* **To Win:** Successfully guide enough fruits into the blender's goal area to reach a juice level greater than 40. Doing so will trigger the "FULL" blender animation and display the "You Won" screen.
* **To Lose:** Avoid dropping fruits on the floor! The game will end and display the "Game Over" screen if you drop more than 5 fruits AND your drop-to-juice ratio exceeds 70%.

## Controls
* **Spacebar:** Start the game from the title or game over screens.
* **Mouse Movement:** Controls the position of the paddle.
* **Mouse Click & Drag:** Changes the paddle's visual state and allows you to "juggle" the fruits, modifying their X and Y velocities based on your mouse's speed and direction.

## Game Mechanics
* **Fruit Physics:** Fruits spawn dynamically and fall with gravity. They can bounce off the screen borders, the table hitbox, and the blender exterior.
* **Blender Animation:** The blender visually fills up as your `juiceLevel` increases, updating its costume dynamically based on your score.
* **Dynamic Spawning:** The game uses a randomized timer and percentage system to spawn different clones of the fruit object at varying intervals.

## Credits & Assets
This project utilizes several audio assets to enhance the gameplay experience:
* **Music:** Includes tracks from *Plants Vs. Zombies* (Grasswalk, Loonboon, Ultimate Battle), *Super Smash Bros* (Dream Land), and *Super Mario Bros*.
* **Sound Effects:** Features "Cartoon Splat", "High Whoosh", "Tap Conga", a custom "Blender_SFX", and standard UI pop sounds.

## Use of AI
In accordance with course guidelines, the following outlines the use of Artificial Intelligence in this project:
* **Assets:** Some graphical and/or audio assets were edited or generated using AI tools.
* **Code & Design:** AI was **strictly not used** for any coding, problem-solving, game design, logic implementation, or structuring. All Scratch block scripting and game mechanics are entirely my own original work.
