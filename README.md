# Othello-Board-Game
Othello board game implemented with Java. Contains simple GUI

Major logic code body missing due to missing files. In the process of recoding the logic section.

Functionality Overview:

The Othello board game has two mode: single player and multiplayer. 

In the Multiplayer mode, two players can :
1. Click on a square to select it and place down his piece. If the square is already occupied or out of bounds,
an error message will appear and prompt the user for another valid input.
2. After placement, the algorithms detect any rows, columns and diagonals that are "trapped" and replaces the "trapped" opponent 
pieces with the current player's piece
3. The opponent takes his turn and the cycle repears until all squares have been filled. The player with the most number of
pieces on board by the end of the game wins the match

In the Single Player mode, the human player can:
1. Click on a square to select it and place down his piece. If the square is already occupied or out of bounds,
an error message will appear and prompt the user for another valid input.
2. After placement, the algorithms detect any rows, columns and diagonals that are "trapped" and replaces the "trapped" opponent 
pieces with the current player's piece
3. The AI takes its turn. It places a piece that optimizes the number of player pieces trapped and prioritizes corners, borders,
and other strategical positions.
4. The opponent takes his turn and the cycle repears until all squares have been filled. The player with the most number of
pieces on board by the end of the game wins the match

The game pieces are two .jpg files. They can be replaced with any other image. 
