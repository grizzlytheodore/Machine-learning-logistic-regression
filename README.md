# Machine-learning-logistic-regression

In depth documentation in ex2.pdf

First part of the exercise was to build a logistic regression model to predict whether a student gets admitted into a university. 
To do that I first plot the data to visualize it. Then I create the prediction fucntion and the cost function. The cost function sums the cost of error from all the predictions. Then I iterate the learning procedure to minimize the cost.

The second part of this exercise I implement regularized logistic regression to predic whether microchips from a fabrication plant passes quality assurance. The procedure is about the same, but regularization is added which avoids overfitting. 

I contributed to following files:
plotData.m - Fuction to plot 2D classification data
sigmoid.m - Sigmoid function
costFunction.m - Logistic Regression cost function
predict.m - logistic regression prediction fuction
costFunctionReg.m regularized logistic regression cost
