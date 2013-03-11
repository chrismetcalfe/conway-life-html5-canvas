Conway's Game of Life
=====================
Conway's game of life is a famous computer science problem first introduced by John Conway in 1970. Life is a “zero­player” game that consists of an 'n' by 'm' checkerboard or grid, with each cell having the possibility of being on or off. The next state of each cell is decided by counting the number of neighboring cells that are on or off (see Rules). More information can be found on [http://en.wikipedia.org/wiki/Conway's_Game_of_Life](Wikipedia).

Canvas
------
This code served as a way for me to learn and experiment with the canvas element that is part of HTML5. My intention is that this code is simple and easy to read such that other people may learn from it. If you have questions or feel you can improve anythying feel free to fork this repo or drop me a line.

Rules
-----
1.  Neighbors: The cells directly north, south, east and west of the current cell.

2.  Overcrowding: If a living cell has more than three living neighbors it will die during the transition to the next generation.

3.  Loneliness: If a living cell has less than two living neighboring cells it will die during the transition to the next generation.

4.  Resurrection: If a dead cell has more than three living neighbors it will come to live during the transition to the next generation. 


