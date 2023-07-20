# Connect-Four-Chessboard-Game

The idea with the game "Connect Four" is for you to lay out four game pieces in a row horizontally, vertically or diagonally before your opponent does. Things you need to consider when implementing this game is to keep track of your current state of game pieces, your opponents and to check for a winner. It's useful when programming to think of game loop, a set of actions you need to repeat until you can declare a winner. Something like so:

Start with a "reset" state, i.e a clean board with no game pieces.
User place game piece.
Opponent place game piece.
Check for winner:
if there's a winner, declare winner and end game, or restart game.
if no winner, repeat step 2.
