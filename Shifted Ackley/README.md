The objective is to solve unconstrained problem : F6 as described in the “CEC2008_TechnicalReport.pdf” for both dimensions D = 50 and D = 500.
F6: Shifted Ackley

The coordinates of the shifted global minimum of this function in dim = 1000 are provided in a numpy array in a data file "data.py". These are the target coordinates to be achieved.
F6: ackleydat -> shape = (1000,)

The fitness or value of this function at its minimum is also available in numpy array "f_bias" in "data.py". This is the the target fitness value to achieve.
f_bias[5] = F6_min = -140

- Algorithm : Genetic Algorithm - The shifted Ackley function is multimodal and as such requires a heuristic-based algorithm that takes advantage of natural selection to avoid local minima.
- Libraries : PyGMO
- Parameters of the algorithm : Number of individuals, number of generations 
- Stopping criterion : number of generations = specified number
- Number of function evaluations : see notebook
- Computational time : see notebook
- Convergence curve : see notebook
- Final results (solution and fitness) : see notebook
