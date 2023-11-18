Gradient-Descent
=================
The main content of this file is the description of the "Gradient Descent Method".
---------------------------------------------------------------------------------
Gradient descent is often used in machine learning to optimize the loss function. In fact, we can introduce the gradient descent method by introducing 'extreme values'. You can start by looking at the function graph below:

There are multiple extreme value points in this image. What the gradient descent method does is to find an 'extreme value point so that the value of the function is as small as possible. To solve this problem, the algorithm starts by "randomly" searching for a location and then starts searching for a "local" optimal solution. If you are lucky, you will be able to find an extremum with the smallest value, but if you are not lucky, you may not find the extremum with the smallest value.
The gradient descent process:
By its name, the gradient is a vector of partial derivatives of a function with respect to each of its independent variables. It is actually finding the derivative of a function. (If there is only one independent variable in the function).
After that, it is constantly updated for the value of x so that its derivative reaches a value very close to zero.
