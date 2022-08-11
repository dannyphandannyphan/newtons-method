# Newton-Raphson Method

Hello! This is my first personal project. In this we will use an interactive Jupyter notebook to find approximate solutions to functions.

### Theory

Essentially, we find the root of a function by producing better and better approximations for it. Given that we have a differentiable function and an initial guess, then we can find a better guess by doing $$x_n+1 = x_n - \frac{f(x_n)}{f'(x_n)}$$
Over and over again until we have a sufficiently strong guess (for me I'd say 4 decimal places is enough).

### Implementation

We will differentiate the function at that point using the definition of the derivative. The guess point will be up to the user.
