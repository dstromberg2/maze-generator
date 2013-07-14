MAZE GENERATOR

A script in Javascript to create a randomly generated maze.

To use, include the mazegenrator.js file, then call the newMaze function with the input parameters for the size of the maze, as x and y variables. Return value is an array defining the new maze.

An example.html file is included to show a possible usage.

The generated maze is defined by a multidimensional array consisting of y and x coordinates, followed by definitions for the borders of each selected cell. The borders are defined using CSS order, which is [top, right, left, bottom], where 0 defines the presence of a wall, and 1 defines no wall.

So if the first cell in the maze is defined as maze[0][0][0,1,1,0], there would be a wall on the top and the left of that particular cell, with openings on the right and bottom.

Note that y coordinates are used first in the array, and x is second. This is to facilitate the display of the maze in HTML, as horizontal rows need to be established first, followed by each vertical cell in the row.

