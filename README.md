# Frogger
**Built with Python's Turtle graphics**  
**Completed as part of Hackbright's Prep course**  
This file contains instructions for installing my program, playing the Frogger game, and future features. I hope you enjoy playing! 

![](images/header-image.jpg)

## Getting Started 

**Installation**  
Download the python file and run it on your machine. When the file is running properly, a game board should appear that looks like this: 

![](images/game-board.png)

**Game Objective**  
The objective of Frogger is to cross to the green finish line without colliding with the bouncing balls. If you hit one of the balls, your frog will return to start. Reach the green line and you win!

**Game Controls**  
Use your keyboard arrows to control your frog. You may move up, down, forwards, and backwards.

**Changing the level of the game**  
You may increase the speed of the balls by updating the argument provided in the main game loop (the last line of the code.) I recommend starting with level three and incrementing up from there. In the screenshot below, you can see where to update the level of the game:

![](images/changing-level.jpg)

## Code Improvements Since version 1

**Random speed and ball direction functionality added**  
I wanted to be sure that each time a user played the game, it would be a different experience. In order to achieve this, I created a list of all the possible speeds and directions that the balls could go, then randomly generated a float to be applied to the movement of the balls. 

**Removal of unnecessary functions**  
Functions were regrouped so that all the object movements were included within the same function. This action removed an uneccessary function.

**Cleaned up formatting**  
Removed unnecessary spaces and unused code from file. Coordinates were reformatted with proper spacing. 

**Added level message**   
A printed message was added to the top corner of the game board to inform the player what level they are currently playing.

**Game loop**   
Game loop was cleaned up. The resulting message after a win was  flashing was corrected and no longer flashing.


