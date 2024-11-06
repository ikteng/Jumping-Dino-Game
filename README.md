# Jumping Dino Game 🦖
A simple, browser-based game inspired by the classic Chrome offline dinosaur game. In this game, the player controls a dinosaur character to jump over incoming obstacles, aiming to achieve the highest possible score without colliding. Built using HTML, CSS, and JavaScript, this project demonstrates fundamental game mechanics and animations in web development.

## 📸 Demo

### Start page
![image](https://github.com/user-attachments/assets/c07dd70c-1b05-4b9e-8ed7-6e835b6478d5)

### Game Running
![image](https://github.com/user-attachments/assets/3a225989-4466-4dda-9a41-f270795b547b)

### Game over
![image](https://github.com/user-attachments/assets/78fbcef2-d311-4da9-9535-63a159732ec9)

## ✨ Features

- **Jump Mechanic**: Press the spacebar to make the dinosaur jump and avoid obstacles.
- **Dynamic Obstacle Generation**: Obstacles are generated at random intervals, creating a continuous challenge.
- **Score Tracking**: Score increases with each successfully dodged obstacle, shown in real-time on the screen.
- **Game Over and Reset**: The game resets when a collision occurs, allowing for easy replayability.
- **Animated Ground Movement**: Adds a dynamic sense of motion to the game environment.

## 🎮 How to Play

- **Start**: Press the spacebar to begin the game.
- **Controls**: Use the spacebar to make the dinosaur jump over obstacles.
- **Objective**: Avoid obstacles for as long as possible to achieve a high score.

The game gets progressively more challenging as you continue playing, encouraging players to improve their reflexes and timing.

## 🛠️ Code Overview

### HTML
Defines the game’s structure, including:
- **Game Container**: Houses the dinosaur character, ground, obstacles, and score display.
- **Start Screen**: Displays a prompt for the player to start the game.

### CSS
Handles the styling and animations for:
- **Ground Movement**: Creates a looped animation for ground movement, simulating a running environment.
- **Obstacle Transitions**: Smoothly animates the obstacles as they move across the screen.
- **Responsive Design**: Ensures the game adapts to different screen sizes.

### JavaScript
Implements core game functionality:
- **Game Start and Jump Mechanics**: Tracks player inputs to start the game and make the dinosaur jump.
- **Obstacle Generation**: Dynamically creates and moves obstacles at timed intervals.
- **Collision Detection**: Checks for collisions between the dinosaur and obstacles to end the game if needed.
- **Score Management**: Tracks the player’s score in real-time, displayed in the top corner.
- **Game Reset**: Resets the game state on collision, allowing players to replay easily.


## 🚀 Installation and Setup
Clone the repository:
   ```bash
   git clone https://github.com/ikteng/Jumping-Dino-Game.git
   ```
