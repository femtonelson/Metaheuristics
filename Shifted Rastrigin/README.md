The objective is to solve unconstrained problem : F4 as described in the “CEC2008_TechnicalReport.pdf” for both dimensions D = 50 and D = 500.
F4: Shifted Rastrigin

The coordinates of the shifted global minimum of this function in dim = 1000 are provided in a numpy array in a data file "data.py". These are the target coordinates to be achieved.
F4: rastrigindat -> shape = (1000,)

The fitness or value of this function at its minimum is also available in numpy array "f_bias" in "data.py". This is the the target fitness value to achieve.
f_bias[3] = F4_min = -330

- Algorithm : Genetic Algorithm<br> Function F4 is highly multimodal with a huge number of local minima. GA can optimize better by mimicing natural selection in low dimensions where gradient-based or deterministic-transition-based heuristics would fail. However as dimensionality grows, GA becomes very computationally intensive.
- Library : PyGMO
- Parameters of the algorithm : Population size, number of generations
- Stopping criterion : Number of generations completed
- Number of function evaluations : see notebook
- Computational time : see notebook
- Convergence curve : see notebook
- Final results (solution and fitness) : see notebook
