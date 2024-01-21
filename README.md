# turtle_Crossing
Player Class (player.py):

Represents the turtle player.
Starts at the bottom of the screen.
Listens for the "Up" keypress to move north.
Checks if it is at the finish line.
CarManager Class (car_manager.py):

Represents the manager for the cars in the game.
Creates cars with different colors.
Moves the cars from right to left.
Increases the speed of cars when the player levels up.
Scoreboard Class (scoreboard.py):

Represents the scoreboard that displays the current level.
Clears the previous level display before updating.
Main Game Loop (main.py):

Sets up the game screen.
Listens for the "Up" keypress to move the player.
Manages the creation and movement of cars.
Checks for collisions and successful crossings.
Updates the level and scoreboard accordingly.
The game dynamically increases in difficulty as the player successfully crosses the screen. It's a simple yet engaging concept that combines user input, animation, and scoring mechanics.
