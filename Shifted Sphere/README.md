The objective is to solve unconstrained problem : F1 as described in the “CEC2008_TechnicalReport.pdf” for both dimensions D = 50 and D = 500.
F1: Shifted Sphere

The coordinates of the shifted global minimum of this function in dim = 1000 are provided in a numpy array in a data file "data.py". These are the target coordinates to be achieved.
F1: spheredat -> shape = (1000,)

The fitness or value of this function at its minimum is also available in numpy array "f_bias" in "data.py". This is the the target fitness value to achieve.
f_bias[0] = F1_min = -450

- Algorithm : Particle Swarm Optimization(PSO). This algorithm is fast and suitable for high dimensions. The conjugate gradient descent algorithm works well on this continuous differentiable function.
- Library : psopy(PSO)
- Parameters of the algorithm : Number of particles in the swarm
- Stopping criterion : stable_iter (the number of iterations with a stable result) = 100
- Number of function evaluations : see notebook
- Computational time : see notebook
- Convergence curve : see notebook
- Final results (solution and fitness) : see notebook
