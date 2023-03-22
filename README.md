# Number-Guessing-Game

The number guessing game is a simple game where the player tries to guess a number that the computer has selected at random. The player is given a certain number of attempts to guess the correct number, and the computer provides feedback after each guess to help the player narrow down their choices.

The basic flow of the game involves the following steps:

* The computer selects a random number within a predefined range (e.g. between 1 and 100).
* The player is given a certain number of attempts to guess the number.
* The player enters a guess.
* The computer checks the guess against the actual number and provides feedback to the player (e.g. "too high" or "too low").
* The player continues guessing until they either guess the correct number or run out of attempts.
* The game ends with a message indicating whether the player won or lost.
* The game can be made more challenging by adding additional rules, such as limiting the number of guesses, changing the range of possible numbers, or adding a time limit. It can also be made more interesting by adding graphics, sound effects, or other interactive elements.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python num.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* import random and import math are imported libraries.

* Two variables lower and upper are taken as input to set the range of the number to be guessed.

* A random number x is generated between the lower and upper range using the random.randint() function.

* A message is printed to the user to inform about the number of chances to guess the correct number, which is calculated using the math.log() function.

* The count variable is initialized to keep track of the number of guesses.

* A while loop is used to prompt the user for their guess until the guess is correct or the maximum number of guesses is reached.

* The formula math.log(upper - lower + 1, 2) is used to calculate the minimum number of guesses required to guess the number correctly.

* The user's guess is taken as input using input() function.

* The user's guess is compared with the randomly generated number x.

* If the user's guess matches the randomly generated number x, a congratulatory message is printed with the number of tries taken.

* If the user's guess is higher than the randomly generated number x, a message is printed informing the user that they guessed too high.

* If the user's guess is lower than the randomly generated number x, a message is printed informing the user that they guessed too low.

* If the user exhausts all the chances to guess the correct number, a message is printed displaying the correct number and informing the user that they could not guess it.

* The program ends.
