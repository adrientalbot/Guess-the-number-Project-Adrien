# Guess-the-number-Project-Adrien

Description:


The purpose of the game is to guess a random number that is between 1 and 100.

The player has 8 guesses to guess the correct number. 

If the player uses all 8 guesses, he looses and the game repeats itself.

If she/he correctly guesses the random number without using all 8 guesses, he/she wins! 



Features: 


- The computer asks the player to select an integer between 1 and 100.

- The computer generates a random integer. 

- If the number chosen by the player is less than the random number, the user is asked to select a higher number. 

- If the number chosen by the player is greater than the random number, the user is asked to select a lower number. 

- If the number of guesses reaches 0 before the user picked the right random number, the player looses! The game then repeats itself!

- However, if the player manages to guess the correct random number before, the program lets the player know that he/she has won. 

- The user can see how many guesses he has left. 



Workflow: 

1) We create a count which keeps track of the number of guesses left. 

2) we will use an input function to ask the user to pick an integer between 1 and 100.

3) Set up a function that generates a random integer from a list of integers within the same range.

4) We will make use of a while/for loop to force the user to change his number if the value he chose was less or greater than the random number we are trying to guess (defensive programming as used in the pre work with the rock paper scissors exercise).

5) In the loop, We keep asking the user to change the value until he correctly guessed the random number.

6) Use IF function to determine at the end if the player has won depending on the number of guesses left and if he has picked the right random number. 


