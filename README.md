# Project Description
In this project I am implementing an AI module for a minesweeper robot in
Haskell. The environment in which the robot operates is an 10 × 10 grid of cells. Initially,
a cell on the grid is either empty, contains the robot, or contains a mine. The robot can
move in all four directions and is able to collect a mine only if it is in the same cell as the
mine. My program will take as input the initial position of the robot and the positions
of all of the mines. The objective of the AI module is to compute a sequence of actions
that the robot can follow in order to go to all the mines and collect them. Below is an
example grid.

![Orientaion](https://github.com/AlaaHisham02/Mine-Sweeper/blob/d7b0d6b080b0a88c703d0e1c8f8869bf99c9d05c/assets/Ori.PNG)

The robot R starts at (3,0) while the mines are at (2,2) and (1,2). One possible generated
sequence of actions by your program is:
["up","right","right","collect","up","collect"]

Examples

![Orientaion](https://github.com/AlaaHisham02/Mine-Sweeper/blob/d7b0d6b080b0a88c703d0e1c8f8869bf99c9d05c/assets/Runs.png)

P.S: It cannot perform on wide scale distaces between mines or numbers.
