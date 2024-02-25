# Rust Snake Game
Welcome to the Rust Snake Game project! This Rust application provides a simple implementation of the classic Snake game. With the Rust Snake Game, users can enjoy a nostalgic gaming experience where they control a snake to eat food and grow longer while avoiding collisions with walls and its own tail.

## Features
1. **Classic Gameplay:** Offers the classic gameplay of Snake, where players control a snake to eat food and grow longer.

2. **Snake Movement:** Allows the player to control the direction of the snake's movement using arrow keys or other configured keys.

3. **Food Generation:** Generates food items at random locations on the game board for the snake to eat and grow longer.

4. **Scoring:** Tracks and displays the player's score based on the number of food items eaten by the snake.

5. **Collision Detection:** Detects collisions between the snake and walls or its own tail, ending the game if a collision occurs.

6. **Game Over Screen:** Displays a game over screen when the snake collides with a wall or its own tail, allowing the player to restart the game.

## Installation
To run the Rust Snake Game, follow these steps:

1. **Clone the Repository:** Clone the repository to your local machine using the following command:

git clone https://github.com/RadinaAvramova/snake-game.git

2. **Navigate to the Directory:** Change your current directory to the location of the cloned repository:

cd snake-game

3. **Build the Application:** Build the Rust binary for the game using Cargo, the Rust package manager:

cargo build --release

## Usage
1. **Start the Game:** Run the built binary to start the Snake game:

cargo run --release

2. **Control the Snake:** Use the arrow keys (or other configured keys) to control the direction of the snake's movement.

3. **Eat Food:** Guide the snake to eat food items displayed on the game board to grow longer and increase your score.

4. **Avoid Collisions:** Avoid collisions with walls or the snake's own tail, as colliding will end the game.

5. **Game Over:** When the game ends, a game over screen will be displayed, allowing you to restart the game.

## Customization
1. **Game Settings:** Customize game settings such as board size, snake speed, food appearance frequency, and initial snake length to tailor the gameplay experience.

2. **Graphics and Sound:** Modify graphics assets and sound effects to change the visual and auditory aspects of the game.

3. **Game Mechanics:** Adjust game mechanics such as collision detection rules, scoring system, or power-up items to introduce new features or variations to the gameplay.
