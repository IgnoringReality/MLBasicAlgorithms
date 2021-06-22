Simple Linear Regression
------------------------

Reference - https://machinelearningmastery.com/implement-simple-linear-regression-scratch-python/ 

Linear Regression assumes a linear relationship between the input variables (X) and the single output variable (y).
The linear relationship can be represented by the equation of a line -

y = ax+b

where a and b are the coefficients we need to estimate.

We can estimate the coefficients as - 

a = sum((x(i) - mean(x)) * (y(i) - mean(y))) / sum( (x(i) - mean(x))^2 )

b = mean(y) - a * mean(x)

where i is the ith input or output value from the dataset.

Dataset Used
------------

The dataset is called the “Auto Insurance in Sweden” dataset and involves predicting the total payment for all the claims in thousands of Swedish Kronor (y) given the total number of claims (x).

Here is a small sample of the first 5 records of the dataset.

108,392.5

19,46.2

13,15.7

124,422.2

40,119.4



