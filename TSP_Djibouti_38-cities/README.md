The objective is to solve a Travelling Salesman Problem (TSP) by finding the shortest path to visit all cities in a country without visiting the same twice. 
**Problem : 38 cities (Djibouti). The optimal tour has length 6656.**<br>
Input data (in TSPLIB format) obtained from the link: http://www.math.uwaterloo.ca/tsp/world/countries.html

- Algorithm : Genetic Algorithm - Chromosomes provide a suitable representation of city sequences and this algorithm is robust enough to guarantee convergence towards the optimal solution in this discrete problem. However it is computationally intensive and requires a proper choice of selection, mutation and crossover strategies. 
- Library : PyGMO
- Parameters of the algorithm : Number of individuals, number of generations, mutation/crossover/selection strategy  
- Parameter tuning : Stepwise comparison of selection/crossover/mutation strategies provided in pygmo package reveals the following best parameters<br>
  selection = "truncated" - selection of best chromosomes over entire population<br>
  crossover = "single" - selecting a random point in the parent chromosome and inserting the partner chromosome thereafter with crossover probability
  mutation = "uniform" - Random sampling from the chromosome bounds<br>
  mutation probability = 0.05
- Stopping criterion : Number of generations = specified value
- Number of function evaluations : see notebook
- Computational time : see notebook
- Convergence curve : see notebook
- Final results (solution and fitness) : see notebook
