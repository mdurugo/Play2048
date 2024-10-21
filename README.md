# Play2048
In this project, the game 2048 is coded and replicated using 2-D arrays, array manipulation, how to navigate references to objects, and the object-oriented programming (OOP) paradigm.

2048 is a puzzle game where you use the arrow keys to move left, right, up or down to merge tiles of the same number together.

The goal of the game is to keep merging numbered (non-zero) tiles until you get one 2048 tile. If two tiles with the same number touch each other, they are merged together in the direction swiped into a new tile with twice the value. (ex: if you move up, the topmost value doubles and the bottom value becomes 0). Be careful with your moves – if the board is full at the end of a turn and there are no other valid moves, it’s game over!

In this project, we will represent the 2048 grid as a 4×4 array of integers, with 0’s representing empty tiles.
