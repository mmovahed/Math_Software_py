# Assignment 03: Optimization with SciPy

## 🌟 Goals
- Learn to define objective functions.
- Solve optimization problems using `scipy.optimize`.

## ✅ Tasks

1. **Minimize a Quadratic Function**  
   - Define the function \( $f(x) = (x - 5)^2$ \)
   - Use `scipy.optimize.minimize` to find its minimum starting from \( $x_0 = 0$ \)

2. **Multivariable Optimization**  
   - Define \( $f(x, y) = x^2 + y^2$ \)
   - Minimize the function using an initial guess of [2, 2]

3. **Constrained Optimization**  
   - Minimize \( $x^2 + y^2$ \) subject to \( $x + y = 1$ \)

4. **Linear Programming**  
   - Use `scipy.optimize.linprog` to solve:
     - minimize \( $-x - 2y$ \)
     - subject to: \( $2x + y \leq 20,\ x + 2y \leq 20$ \)
     - and \( $x, y \geq 0$ \)

## 🌟 Optional Challenge
- Visualize the feasible region and the objective function using Matplotlib for the linear programming problem.

## 📌 Instructions
- Save your answers in a notebook named `assignment_03.ipynb`.
- Comment each section to explain the steps and results.
