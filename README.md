This code runs a simplified version of poker.
Right off the bat, we import counter from collections, sys, random, and time. 
Counter: This is used to properly order the cards in numerical order when evaluating hand values.
sys: This is used to exit when the user says that they do not wish to play again.
random: Used to randomly select a card suit and and number
time: Used to pause for a second in between lines of code, helps the run of the code (Smoother gameplay)

Next, variables are initialized. The money you start with, the money you have in total, , the number of cards dealt so far, and the current bet are all initialized to sperate values. Also, ai (all in) is set to n, to tell the game that the user has not gone all in yet.

Next we have the dictionarys, the first is cards, showing all of the cards and their numerical value, and the second being the suits. And the sets, blank at first, that are used to store the cards dealt so far.

Now the functions, they are all defined in my planner, but ill sumarise them here. 
-First deal(), used to deal out your two cards. 
-Second, comdeal(), used to deal the computors two cards, done behind the scenes so you dont actually know their hand. 
-Betting(),used to allow you to make the initial bet in the first round
-game_timw(), used to allow the user to make a decision wether they want to call, fold, check, raise, or go all in.
-river(), used to deal out the community cards.
-other_gambling(), used to create the computer bet, uses simple logic to make a somewhat educated bet.
-hands(), used to evaluate your cards to find out what hand you have, then give it a value
-com_hands(), used to evaluate the computors cards to find what hand they have and assign a value.
-playagan(), used to loop the code once the user plays  
-loop(), used to run all of the functions, this is where the game is played, in playagan, this is the function that is looped.
