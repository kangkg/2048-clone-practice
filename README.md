# A 2048 Clone

This is just some practice to make a clone of the game [2048](http://gabrielecirulli.github.io/2048/).

This project utilizes object-oriented javascript, and integrates itself with the HTML interface. 
It also utilizes Canvas and Mousetrap. 

## How to Install:
Clone this repo. Simply run/open `index.html` and play!

## Unfinished bugs:

The game is fairly robust, except for one small bug: instances of the same numbers will always prioritize the right-side first; for example, a column with `0-2-2-2` when pushed left should become `4-2-0-0`, but it incorrectly becomes '2-4-0-0'. 
