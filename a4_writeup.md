# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
When I was coding, there was slight inconsistencys within my methods so an attribute error popped up and I had to comb through my code to fix it just to see it was a misplaced _ that was creating this error

2. Explain how you would add a computer player to the game.
Add an ai that could read the players move by searching each lists array and check which * is replaced with the players O or X and then place a X or O in the appropriate square depending on the CPUs level to best win.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
Import an API with each possible algorithm of tic tac toe moves per each move such as 1 2 3 4 5 6 7 moves and everytime the player makes a move check through the API to match the lists like the match function we previously used and then whichever array it matches up with it plays the move that the array has. Ex. if player played top right X then the AI would play middle bottom O. 