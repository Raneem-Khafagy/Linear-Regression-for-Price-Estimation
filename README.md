# Linear Regression in Pricing Estimation

Linear regression follows the linear mathematical model for determining the value of one dependent variable from the value of one or multiple variables.
**y=mx+c**
where y is the dependent variable, m is the slope, x is the independent variable and c is the intercept for a given line.
## The Data
It contains 97 training data points for the [One variable model](#one-variable-linear-regression-model) with only one feature which is the **size of the house** and 47 training data points with additional feature **number of rooms in the house** for the [Multiple variable model](#multi-variable-linear-regression-model) those features help us predict the selling price of a house. 

### Loss function
used Mean Squared Error (MSE) Cost Function
to measure how much the average model predictions vary from the correct values.
### optimization [ Gradient Descent ]
I used **Gradient Descent** an optimization algorithm, to update the parameters of our model
by iteratively moving in the direction of steepest descent as defined by the negative of the gradient.
## One variable linear regression model
<p align="center">
 The following graph shows the decay of loss function aginist the number of iterations 
</p>

![loss function](https://github.com/Raneem-Khafagy/Linear-Regression-for-Price-Estimation/blob/main/oneVarLinearRegression/screenshots/loss_function_plot.jpg?raw=true)
<p align="center">
The following table shows the predicted price compared to the real one
</p>

![predictions](https://github.com/Raneem-Khafagy/Linear-Regression-for-Price-Estimation/blob/main/oneVarLinearRegression/screenshots/predictions.jpg?raw=true)

## Multi variable linear regression model
<p align="center">
 The following graph shows the decay of loss function aginist the number of iterations 
</p>

![loss function](https://github.com/Raneem-Khafagy/Linear-Regression-for-Price-Estimation/blob/main/multiVarLinearRegression/screenshots/loss_function_plot.jpg?raw=true)

<p align="center"></p>
The following table shows the predicted price compared to the real one
</p>

![predictions](https://github.com/Raneem-Khafagy/Linear-Regression-for-Price-Estimation/blob/main/multiVarLinearRegression/screenshots/predictions.jpg?raw=true)
<<<<<<< HEAD



=======
>>>>>>> 59e2e61dc1252789bf25733383367f5536fa0204
