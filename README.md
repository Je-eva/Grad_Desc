HELLO VIEWERS, HERES A QUICK README TO THE PROVIDED CODE

Firstly, accept user inputs to enter coefficients of a cubic equation , in float and map() is used to enter all the coefficients at a time separated by space.
Then,we initialize vaariable x with random value using numpy.random.rand().
We set the parameters ie learning rate and  no of epoches, where the learning rate determines the step size taken during each iteration of SGD, and epochs represent the number of iterations over the entire dataset.

WE then enter the SGD Training Loop, which iterates "epoch" times, wich calculates cubic equation with respect to x .
Then the value of x(gradient) is updated using SGD update rule.
ReLu  is used to  handle when x<0
Finally result is printed, which is the final value of x which will be an approximation of a solution to cubic equation.


TLDR:, The program implements stochastic gradient descent (SGD) to find a solution to a cubic equation 
specified by the user's input coefficients. It iteratively updates the variable x to minimize the value of the cubic equation.



