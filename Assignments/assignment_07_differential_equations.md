# Assignment 07: Differential Equations with SciPy

## 🌟 Goals
- Learn to solve ordinary differential equations using `solve_ivp`.
- Interpret and visualize the solutions.

## ✅ Tasks

1. **First-Order ODE**  
   - Solve \( $\frac{dy}{dt} = -3y$ \) with \( $y(0) = 2$ \) for \( $t \in [0, 5]$ \).
   - Plot the solution.

2. **Second-Order ODE (converted to system)**  
   - Solve \( $\frac{d^2y}{dt^2} + y = 0$ \), equivalent to:
     \[ $\frac{dy_1}{dt} = y_2 \;\;
         \frac{dy_2}{dt} = -y_1$ \]
   - Use initial conditions: \( $y_1(0) = 0, y_2(0) = 1$ \)
   - Plot \( $y_1(t)$ \)

3. **System of ODEs**  
   - Solve the system:
     \[ $\frac{dx}{dt} = x - y \;\;
        \frac{dy}{dt} = x + y$ \]
   - Use initial condition \( $x(0) = 1, y(0) = 0$ \), and plot both variables.

## 🌟 Optional Challenge
- Write a function that takes a first-order ODE as input and returns its solution and plot over a given interval.

## 📌 Instructions
- Save your answers in a notebook named `assignment_07.ipynb`.
- Add explanations, plots, and comments for clarity.
