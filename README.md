## A simple genetic algorithm to solve the travelling salesman problem

In traveling salesman problem, salesman has to visit all cities in this distance matrix only once with a SHORTEST path.

Here is the simple algorithmic step of this algorithm:

1. Construct a square matrix of distances between cities (randomly).

2. Construct a random initial population (e.g., 1000 individuals) (Random solutions including list of cities together with their corresponding total distances which is the entity we want to minimize)

3. Sort the initial population in terms of total distances.

4. Apply a sinle-point crossover operator for paired solutions.

5. Apply mutation operator

6. Check for termination
