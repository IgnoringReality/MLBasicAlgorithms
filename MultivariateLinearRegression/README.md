# Multivariate Linear Regression

Still a linear relation, but multiple input variables decide one output variable.

y = a0 + a1 * x1 +a2 * x2 + a3 * x3 + . . . 

Gradient Descent is the process of minimizing a function by following the gradients of the cost function.

This involves knowing the form of the cost as well as the derivative so that from a given point you know the gradient and can move in that direction, e.g. downhill towards the minimum value.

Each iteration, the coefficients (a) in machine learning language are updated using the equation:

a = a - learning_rate * error * x

Where a is the coefficient or weight being optimized, learning_rate is a learning rate that you must configure (e.g. 0.01), error is the prediction error for the model on the training data attributed to the weight, and x is the input value.

# Dataset used

After we develop our linear regression algorithm with stochastic gradient descent, we will use it to model the wine quality dataset.

This dataset is comprised of the details of 4,898 white wines including measurements like acidity and pH. The goal is to use these objective measures to predict the wine quality on a scale between 0 and 10.

