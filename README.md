# Simple-Linear-Regression
1) Delivery_time -> Predict delivery time using sorting time  
2) Salary_hike -> Build a prediction model for Salary_hike    
3) Build a simple linear regression model by performing EDA and do necessary transformations and select the best model using R or Python.

-----------------------------------------------------------------------------------------------------------------------------------------------------------
Linear Regression is a Machine Learning algorithm that falls under Supervised Learning method where historic data is labelled and used to determine the value of the output/dependent variable based on the predictor/independent variable/s. Here as the name suggests, the relationship between the dependent and independent variables is assumed to be linear.

Simple Linear Regression: Only one predictor variable is used to predict the values of dependent variable. Equation of the line: y = c + mX. Where
y : dependent variable
X: predictor variable
m: slope of the line defining relationship between X and y, also called co-efficient of X
c: intercept

The aim of linear regression is to find the best fit line for given X and y variables such that we get optimal values for c and m in the above equation.

Best Fit Line:
We know that scatter plot is used to see how two numeric variables are related to each other and often if there is a linear relationship, we try to fit a line. But we cannot call any line as the Best Fit Line.
Our data contains a set of values for dependent variable (denoted by y) and independent variable/s (denoted by X) and a best fit line is the one for which the Residual Sum of Squares of error terms is minimum. What are error terms? Let’s find out.
So there will be a ‘y’ value given by our line (we call it y_pred) and a ‘y’ value which is already present in our data (we call it y_true). The difference between y_true and y_pred gives us the error term (e). There will be an error term associated with each X and y value.
This error term may be positive or negative. So we take square or all the error terms and sum it. This is called Residual Sum of Squares of error terms.
So the aim of linear regression
 is to find the best fit line for given X and y variables such that the Residual Sum of Squares of errors is minimum. In mathematical terms this RSS is our cost function which we need to minimize. There are several minimization techniques, but the most used is Gradient Descent method.
 
 
