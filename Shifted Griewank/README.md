The objective is to solve unconstrained problem : F5 as described in the “CEC2008_TechnicalReport.pdf” for both dimensions D = 50 and D = 500.
F5: Shifted Griewank

The coordinates of the shifted global minimum of this function in dim = 1000 are provided in a numpy array in a data file "data.py". These are the target coordinates to be achieved.
F5: griewankdat -> shape = (1000,)

The fitness or value of this function at its minimum is also available in numpy array "f_bias" in "data.py". This is the the target fitness value to achieve.
f_bias[4] = F5_min = -180


- Algorithm : Particle Swarm Optimization - The shifted Griewank function is multimodal and as such requires a heuristic-based algorithm. PSO is chosen for it's low computational cost. 
- Library : psopy
- Parameters of the algorithm : Number of particles, stable_iter(Number of iterations to wait before Swarm is declared stable) 
- Stopping criterion : stable_iter = 100
- Number of function evaluations : see notebook
- Computational time : see notebook
- Convergence curve : see notebook
- Final results (solution and fitness) : see notebook
