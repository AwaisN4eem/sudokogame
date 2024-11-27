**Sudoku Solver**
Steps:
1. Generating a Random Sudoku Board :
Randomly fills a Sudoku board with numbers ranging from 1 to 9. While making sure it is
a valid sudoku board without any repetition
2. Solving Sudoku
My solution utilized backtracking algorithm to fill in the empty cells of the Sudoku
board, it selects empty cells tries to bruteforce and check if the number is valid then it
backtracks for further solution. And make it more efficient and fast i used arc consistency
algorithm by using arc consistency algorithm we are able to remove useless possibilities and
reduce our possible search space making the solution faster and also for finding which empty
location to fill i used The MRV(minimum remaining values) heuristic
3. Results Obtained:
The program is very efficient in generating and solving Sudoku puzzles. It gives a
solution if one exists, else tells if no solution is possible. Below is example solution for my
program
**Magic Square solver**
Steps for Solving:
1. Calculating fitness:
The fitness of each child is calculated by subtracting the sum of each rows, columns,
and diagonals from 15.
2. Crossover:
I do a crossover between two parents by selecting random elements from both parent
based on a probability of 50 percent
3. Mutation
I mutate some of the children by swapping two random numbers in the grid.
4. Genetic Algorithm:
By combining the above methods i implemented the genetic algorithm i iterated through
1000s of generation preserved 10 percent of it did crossover for 50 % of it and did mutation for
the rest in the end by repetitions of all this process i was able to get a solution to the problem
Printing the Solution:
Results Obtained:
The genetic algorithm efficiently finds a solution to the 3x3 magic square puzzle. It prints the
solution if found and also how many generations it took to found one and tells if no solution is
possible
