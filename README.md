# Derivative Approximation and Symbolic Differentiation

This code snippet demonstrates the concept of derivative approximation using finite differences and symbolic differentiation with the `sympy` library. Here's a breakdown of what each part does:

## 1. Finite Differences for Derivative Approximation:
- It calculates the derivative approximation of a simple function using finite differences. 
- The first example computes the derivative of $\( J(w) = w^2 \)$ at $\( w = 3 \)$ using a small epsilon value, and then at $\( w = 3 \)$ with a much smaller epsilon.
- Similarly, it calculates the derivative of $\( J(w) = 2w \)$ at $\( w = -3 \)$ using finite differences.

## 2. Symbolic Differentiation with Sympy:
- It demonstrates symbolic differentiation using the `sympy` library.
- The code defines a symbolic variable $\( w \)$ and a function $\( J(w) = w^3 \)$.
- It then calculates the derivative of $\( J(w) \)$ with respect to $\( w \)$ symbolically using `sympy`.
- The calculated derivative is evaluated at \( w = 2 \) to get the exact derivative value.

## 3. Further Examples:
- Additional examples are provided for functions like $\( J(w) = \frac{1}{w} \)$ and $\( J(w) = \frac{1}{w^2} \)$.
- These examples showcase how to calculate derivatives and approximate their values using finite differences.

Understanding derivatives is crucial in optimization algorithms like gradient descent, where derivatives are used to find the direction of steepest descent. Symbolic differentiation allows for exact calculation of derivatives, while finite differences provide a numerical approximation, useful when symbolic differentiation is not feasible.

By combining both techniques, you can better understand the behavior of functions and optimize them effectively in various machine learning and optimization tasks.
