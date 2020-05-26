The objective is to solve unconstrained problem : F2 as described in the “CEC2008_TechnicalReport.pdf” for both dimensions D = 50 and D = 500.
F2: Shifted Schwefel

The coordinates of the shifted global minimum of this function in dim = 1000 are provided in a numpy array in a data file "data.py". These are the target coordinates to be achieved.
F2: schwefeldat -> shape = (1000,)

The fitness or value of this function at its minimum is also available in numpy array "f_bias" in "data.py". This is the the target fitness value to achieve.
f_bias[1] = F2_min = -450

Algorithm : Particle Swarm Optimization - The shifted schwefel function is not differentiable throughout the search space. As such, a gradient-based method produces unstable results and does not guarantee convergence. The heuristic-based PSO algorithm is suitable for this unconstrained, non-linear, unimodal problem in the continuous domain.
Library : psopy
Parameters of the algorithm : Number of particles, stable_iter(Number of iterations to wait before Swarm is declared stable)
Stopping criterion : stable_iter = 100
Number of function evaluations : see notebook
Computational time : see notebook
Convergence curve : see notebook
Final results (solution and fitness) : see notebook
