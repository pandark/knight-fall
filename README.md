Knight Fall
===========

This Open Web App is very much inspired by Alexey Pajitnov's 1990
"Knight Move" game.

## Development
<pre>git clone git://github.com/Pandark/knight-fall.git</pre>

## Installation
TODO (Open Web App manifest)

## Game rules

There is a board.

┌─┬─┬─┬─┬─┬─┬─┬─┐  
├─┼─┼─┼─┼─┼─┼─┼─┤  
├─┼─┼─┼─┼─┼─┼─┼─┤  
├─┼─┼─┼─┼─┼─┼─┼─┤  
└─┴─┴─┴─┴─┴─┴─┴─┘  

There is a knight (the chess piece) on it.

♞

The knight always moves one square in one direction and two in another
one (which is often described as a L shape).

Each time the knight steps on a square, the square is weakened and its
color becomes darker, until the square falls apart, leaving a hole.

If the knight falls in a hole, the game is over.

Hearts with a number on them will appear on the board.
If the counter on the heart reach 0, the heart will disappear.

❤

If you step on a square with a heart, every square will be fully
restored and your score will increase for every reparation.
