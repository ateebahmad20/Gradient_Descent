Since machine learning algorithms are implemented on a computer, the mathematical formulations are expressed as numerical optimization methods. 
Training a machine learning model often boils down to finding a good set of parameters. 
The notion of “good” is determined by the objective function (loss function). Given an objective function, finding the best value of parameters is done by using optimization algorithms.

If our objective function is differentiable, we have access to a gradient at each location in the space to help us find the optimum value. 
By convention, most objective functions in machine learning are intended to be minimized, that is, the best value is the minimum value. 
Intuitively finding the best value is like finding the valleys of the objective function, and the gradients point us uphill. 
The idea is to move downhill (opposite to the gradient) and hope to find the deepest point. 
