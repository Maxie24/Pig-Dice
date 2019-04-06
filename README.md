# Pig-Dice
#### This project is a website based game emulating the nomal rolling and tossing of a dice
#### By **Max Maina**
## Description
Players throw a dice and scores as many points as the total shown on the dice providing the dice doesn’t roll to a 1. The player may continue rolling and accumulating points (but risking not to roll a 1) as this will end his/her turn,maning that they lose all points they accumulated that turn, and they pass the dice to the next player. The game goes on where the dice passes from player to player until a winner is determined. The first player to score 100 or more wins the game.
Check it out -> 

## Setup/Installation Requirements  
* Open "pig-dice" directory on terminal
* initialize the project with git  ```git init```
* Go to github.com and create a new repository
* create a remote repository on your computer using terminal and push your work to github.
* create a branch gh-pages and push the directory once more using gh-pages as the branch.
* Go to github click on environment and click to view the website.
* Or rather you can click on the link to clone the project into your folder directory. :
### BDD
In order for the program to run well and to give the correct output, the code had to meet certain criteria
1. The user has to select one choice from the list provided.  
2. For the answer to be correct the value of the label has to be five.
Below is a table to describe this:

## BDD 
| Behavior                          |  Input Example |  Output  Example|
|----------                         |:-------------: |------:      
|  Player 1 clicks Roll |  Click roll    |  Number is generated.  |
|If Player rolls any number other than 1, roll is added to round total   | Roll = 3     |  Round Total =3    |
|If Player1 rolls 1, no score is added and it is players 2 turn to roll  |  Roll = 1    |  Round Total = 0, Score = 0,  alerts *pass to the next player*    |
|If Player1 clicks Hold, round total is added to his score and it's Player2 Turn | Click Hold     |  Round Total = 5, Score = 8, alerts *pass to the next player*    |
| When a player's total score is 100 or more points, the game is over and winner alert shows  |  Player 1 score = 105	    |  *WOO-HOO!! You Win*    |
## Known Bugs
There are no major known Bugs but is still under perfection.
## Technologies Used
* HTML to create the website and CSS to style it.
* Codes and README written down on vs code
* JavaScript to create the funcionality for the whole board to work
* jQuery to create a functionality code that displays the scores.
* Bootstrap to style the website easily
* Git used as a version control tool

## Live Link


## Support and contact details
If any issues arise or you need clarifications on anything related, feel free to reach me at;- Cell-0707949131
                      Email-maxmainer0@gmail.com
                      FaceBook-Max Maina
                      Instagram-@maxsta_r
### License
* *MIT.*
* Copyright (c) 2019
