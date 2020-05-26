The objective is to solve unconstrained problem : F3 as described in the “CEC2008_TechnicalReport.pdf” for both dimensions D = 50 and D = 500.
F3: Shifted Rosenbrock

The coordinates of the shifted global minimum of this function in dim = 1000 are provided in a numpy array in a data file "data.py". These are the target coordinates to be achieved.
F3: rosenbrockdat -> shape = (1000,)

The fitness or value of this function at its minimum is also available in numpy array "f_bias" in "data.py". This is the the target fitness value to achieve.
f_bias[2] = F3_min = 390

- Algorithm : Particle Swarm Optimization because it is a fast algorithm and is suitable for this continuous problem. Also the non-linear conjugate gradient works well. Function F3 is multimodal, quadratic, continuous and derivable (smooth) and despite the very narrow valley from local optimum to global optimum, the deterministic Conjugate Gradient algorithm converges to the global optimum in a reasonable time.
- Library : psopy(PSO)
- Parameters of the algorithm : Number of particles, stable_iter(Number of iterations to wait before Swarm is declared stable) 
- Stopping criterion : stable_iter = 100
- Number of function evaluations : see notebook
- Computational time : see notebook
- Convergence curve : see notebook
- Final results (solution and fitness) : see notebook
