# Gradient Descent Optimization with Backtracking and Exact Line Search

This project demonstrates the use of gradient descent optimization techniques to find the optimal point of a complex function. The primary focus is on implementing and comparing two line search methods: Backtracking Line Search and Exact Line Search.

Project Overview
Gradient descent is an essential optimization technique widely used in machine learning and data science to minimize functions. In this project, we implement two methods to adjust the learning rate dynamically:

Backtracking Line Search - A heuristic approach that reduces the step size (alpha) iteratively until a specific condition is satisfied, ensuring the function value decreases sufficiently at each step.

Exact Line Search - A method that computes the exact step size required to minimize the function along a given search direction, offering precise control over the descent path.

Key Features
Backtracking Line Search Algorithm: Implements a dynamic step size adjustment based on the Armijo condition, which ensures that each step moves in the direction of decreasing function values. Parameters used include:

alpha_init = 0.15: Initial step size.
gamma = 0.7: Condition control factor.
beta = 0.8: Factor by which the step size is reduced iteratively.
min_alpha = 1e-2: Minimum threshold to prevent infinite reduction of alpha.
Exact Line Search Algorithm: Provides a calculated step size that precisely minimizes the function along the direction of the gradient, leading to efficient and reliable convergence.

Visualization:

Contour Plot of the Optimization Path: Displays the trajectory of the optimization process, allowing us to observe the convergence toward the optimal point.
Function Values over Iterations: Tracks the function value at each iteration, illustrating how the algorithm progresses toward the minimum.
