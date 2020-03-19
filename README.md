# CSS342-Recursion
Understanding recursion, solving mazes, working with multiple ADTs.
For this assignment, you will write a program that can solve a maze.

Implement the Maze constructor and the ​operator<<​ for Maze first. 
You will need them when debugging your code.

You can use ​ifstream​ to read from a text file. The text file has 
to in the same directory as the executable. In the case of CLion, 
you will need to put it in cmake-build-debug directory.

You can use ​>>​ to read integers, but to read blank spaces you need 
to use ​get function. To read the invisible end-of-line characters, 
you can use ​getline​ and discard what is read.
Confirm that your maze.txt file has spaces rather than tabs

You can use ​char field[MAX_SIZE][MAX_SIZE]​ or ​int
field[MAX_SIZE][MAX_SIZE]​ to store your maze. ​char​ might be easier
since you do not have to convert back and forth between different representations.

Calling ​Creature::goNorth ​and passing the path-so-far by 
reference is one way to keep track of the path. There are other ways
depending on how you implement it.

You should write the algorithm to solve the maze first and 
then work on adding pathstring.

Start with simple mazes. Mazes where creature is already 
at exit or where creature only has to go North to get to exit 
before moving to more complex ones.
