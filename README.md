# Hi This is a guess the number game   
## Features   
#### Three difficulty levels:  
1. Easy → numbers from 1 to 10  
2. Medium → numbers from 1 to 100  
3. Hard → numbers from 1 to 1000     
* Limited attempts depending on difficulty  
* Random number generation using the Python random library  
* User input handling Hints after every attempt   
* Console-based gameplay    
* Simple and beginner-friendly code structure
__________
## Tech Stack
* Python 3  
* Built-in random library
_____________________  
## How the Code Works
1. The program asks the player to choose a difficulty level:
   * Easy
   * Medium
   * Hard    
2. Based on the selected level:
   * The game sets the number range.
   * The game sets the number of attempts.  
3. The random library generates a secret number.  
4. The player enters guesses through the console. 
5. After each guess:   
   * The program checks if the number is correct.  
   * If the guess is too high or too low, the player receives a hint.  
6. The game continues until:    
  * The player guesses the correct number. 
  * Or all attempts are used.   
7. At the end, the program displays:
  * A winning message if the number was guessed.
  * Or the correct number if the player loses.   
