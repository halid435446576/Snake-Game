# Snake-Game

Snake Game
This is a classic snake game implemented using Python's turtle module. The game consists of a snake that moves around the screen, eating food to grow longer, while avoiding collisions with the screen edges and itself. The player's goal is to achieve the highest score possible.

Table of Contents
Installation
Usage
Files
Gameplay
Credits
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/snake-game.git
cd snake-game
Ensure you have Python installed:
This game is written in Python. You can download and install Python from here.

Install the necessary dependencies:
This game uses the turtle module, which is included in the standard Python library. No additional packages are required.

Usage
To start the game, run the main.py script:

bash
Copy code
python main.py
Files
main.py: The main script that initializes the game and contains the game loop.
snake.py: Contains the Snake class that defines the snake's behavior.
food.py: Contains the Food class that defines the food's behavior.
score_board.py: Contains the Score class that handles the game's scorekeeping.
Gameplay
Use the arrow keys to control the direction of the snake:

Up Arrow: Move up
Down Arrow: Move down
Left Arrow: Move left
Right Arrow: Move right
The snake moves continuously in the current direction. Your goal is to eat the food that appears on the screen. Each time the snake eats the food, it grows longer and the score increases.

If the snake collides with the screen edges or itself, the game resets, and the current score is compared with the high score, which is saved in a high_score.txt file.

Credits
This game was created as a coding exercise to practice Python programming and the turtle module. Special thanks to the developers and the community that created and maintains the turtle module.
