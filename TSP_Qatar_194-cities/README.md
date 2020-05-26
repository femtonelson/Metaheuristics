The objective is to solve a Travelling Salesman Problem (TSP) by finding the shortest path to visit all cities in a country without visiting the same twice. 
**Problem : 194 cities (Qatar). The optimal tour has length 9352.**<br>
Input data (in TSPLIB format) obtained from the link: http://www.math.uwaterloo.ca/tsp/world/countries.html

- Algorithm : Genetic Algorithm - Chromosomes provide a suitable representation of city sequences and this algorithm is robust enough to guarantee convergence towards the optimal solution in this discrete problem. However it is computationally intensive and requires a proper choice of selection, mutation and crossover strategies. 
- Library : PyGMO
- Parameters of the algorithm : Number of individuals, number of generations, mutation/crossover/selection strategy  
- Parameter tuning : Stepwise comparison of selection/crossover/mutation strategies provided in pygmo package is necessary<br>
- Stopping criterion : Number of generations = specified value
- Number of function evaluations : see notebook
- Computational time : see notebook
- Convergence curve : see notebook
- Final results (solution and fitness) : see notebook
