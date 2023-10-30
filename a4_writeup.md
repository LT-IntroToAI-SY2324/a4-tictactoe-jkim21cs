# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
   
    I think completing the has_won method was "difficult" only because I forgot python can increment with for loops which makes solving the method much easier than the previous way of solving. 

2. Explain how you would add a computer player to the game.
    
    To add a computer player, it will be necessary to teach the game how to "defend" and look for the best locations to play their turn. In order to do this, you would have to program the computer to recognize the 8 ways to win (they check to see if any of the ways have astericks or their player (X,O) to see where it would be best to place their next turn) or if te opposing player has 2 of their slots (ie. double O) filled which would indicate to the computer that they would need to block the last slot. 

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
    
    The computer would need to "defend" first before playing a move that increases their chance of winning. If no defense is needed, the computer can check to see where there chances of winning are higher (ie. if a way of winning is already hindered by the other player, the computer doesn't attempt to put their player in that slot or if only their player and astericks are in one of the 8 ways, they play in those favorable slots)