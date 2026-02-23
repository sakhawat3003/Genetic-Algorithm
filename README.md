This project presents a simple implementation of a genetic algorithm to illustrate how populations evolve toward optimal solutions. By applying a fitness function and iteratively refining candidates, the algorithm converges to the best-performing solution.

In this notebook, we will walk through each step—population initialization, fitness evaluation, parent selection, crossover, mutation, and replacement. We will see how these processes combine to solve an optimization problem.

This algorithm has the following rules:

- Find a population of solutions for a certain problem or function
- Create a fitness function to measure the performance of each solution
- Select the 2 top most solutions (parents)
- Represent the performance of each solution by Binary number
- Random crossover at any point between these two solutions (child)
- Mutate any binary digit of the child randomly
- Find the worst performer from the population
- Replace the worst performer with the new child
- Repeat the whole process for many generations to get an optimum solution.
