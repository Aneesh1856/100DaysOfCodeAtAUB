# 🚀 Day 20/100: Snake Game in Python! 🐍🎮



Today, I built a classic Snake game using Python and the turtle module! This project was a fun way to practice OOP (Object-Oriented Programming), event handling, and collision detection.



🛠 How It Works:

The game starts with a small snake that moves continuously in the direction of the arrow keys. The objective is to eat food (a small blue dot) that appears randomly on the screen. Every time the snake eats food, it grows in length and the score increases.

However, if the snake collides with the walls or itself, the game ends with a "Game Over" message.



🔗 Code Breakdown:

📌 main.py – The Game Controller

Initializes the screen, snake, food, and scoreboard.

Listens for keypresses to control the snake’s direction.

Runs the game loop to continuously update the screen and check for collisions.

📌 snake.py – Handles Snake Movement

Uses a list of square segments to represent the snake.

Moves forward in steps, and each segment follows the one ahead.

Changes direction based on keypresses while preventing 180-degree reversals.

📌 food.py – Manages Food Spawning

Generates food at random positions on the screen.

Refreshes when the snake eats it.

📌 scoreboard.py – Displays the Score

Tracks and updates the score.

Shows “Game Over” when the player loses.
