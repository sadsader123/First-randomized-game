# First-randomized-game
This is my first attempt at making a game , using Kotlin.

One main thing to note is once the game is complete, there's no way to initialize it again until you fully exit the process or restart the process again. 

Other than that the premise is simple. 

You face a bot that has 3 points already, the point of the game is the user and the bot both choose a number from 0 to 20, 
and depending on the bots and users choices, the number will either be odd or even

the main objective is to try to beat the bot before it gets 10 points,
the user gets points by guessing the outcome correctly. 

this is almost impossible to do without taking the streak option which is triggered when the user guesses 2 times correctly,
in which case the user can gain 3 points but now can lose 2 points for each wrong guess. the bot only ever gets 1 point for the user being wrong.
