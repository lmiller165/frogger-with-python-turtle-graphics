# Hackbright Scholarship Application 
**Laura Miller**  
**Cohort start date: September 30th, 2019**  
Thank you for taking the time to review my application. This file contains instructions for installing my program, playing the Frogger game, and the improvements that were made to my code since it was submitted as a final project in the Prep Course. I hope you enjoy playing! 

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

## Code Improvements

**Random speed and ball direction functionality added**  
I wanted to be sure that each time a user played the game, it would be a different experience. In order to achieve this, I created a list of all the possible speeds and directions that the balls could go then randomly generated a float to be applied to the movement of the balls. 

**Removal of unnecessary functions**  
Functions were regrouped so that all the object movements were included within the same function. This action removed an uneccessary function.

**Cleaned up formatting**  
Removed unnecessary spaces and unused code from file. Coordinates were reformatted with proper spacing. 

**Added level message**   
Printed message was added to the top corner of the game board to inform the player what level they are currently playing.

**Game loop**   
Game loop was cleaned up. The resulting message after a win was  flashing was corrected and no longer flashing.


## Acknowledgements 
Special thanks to:  

**Inhye Baik**    
For taking the time to review my code, provide valuable feedback, and share her experiences as a Hackbrighter.  

**Danielle Yasso**   
For grabbing a coffee with me to share her experiences as a Hackbrighter, tips for job search afterwards, and what she has accomplished since completing the program. 

**Bianca Gandolfo**  
For sharing her experiences completing Hack Reactor, her current role at Thumbtack, and her love of mentoring with Girls Who Code. 

I am so grateful to all these women for their kindness, words of encouragement, and support. I look forward to becoming part of the women in tech community!
