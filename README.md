# Linear-Polinomial-Regression
Linear Regression:
•	Regression is used to predict a numerical label. This means your output can take an infinite set of values, like in the example of predicting an apartment's market value above.
What problems can be solved using linear regression?
You can see how knowing your algorithm's category enables you to identify what problems you can use it for. In simple terms, any problem with the output being a numerical value can use linear regression.
In addition to the apartment value prediction mentioned above, here are several other examples:
•	Predicting taxi fare based on distance traveled
•	Predicting rainfall based on time of the year and location
•	Predicting the homicide rate in the area based on income level and the prevalence of gun ownership
How does the linear regression algorithm work?
Linear regression models are often fitted using the least-squares approach. This requires finding the values of the parameters described in a linear equation of the ‘best-fit line,’ which is achieved by minimizing the sum of squared residuals.
the best-fit line would have the following equation y=ax+b, where y is the output (dependent) variable, x is the input (independent) variable, and a and b are the parameters known as slope and intercept.
Note, linear regression is not limited to using only 1 input variable. In fact, you can use as many input variables as you like. This is known as multiple linear regression. 
How can I use linear regression to build a model in Python?
The two examples in this section are:
•	simple linear regression (using 1 input variable)
•	multiple linear regression (using 2 input variables). Note, I chose 2 input variables instead of, say, 5 because I wanted to draw a chart to help you visualize the solution. However, multiple linear regression can handle as many inputs as you like.
Polinomial Regression:
•	Polynomial Regression does not require the relationship between the independent and dependent variables to be linear in the data set,This is also one of the main difference between the Linear and Polynomial Regression.
•	Polynomial Regression is a form of regression analysis in which the relationship between the independent variables and dependent variables are modeled in the nth degree polynomial.
•	Polynomial Regression is a special case of Linear Regression where we fit the polynomial equation on the data with a curvilinear relationship between the dependent and independent variables.
A Quadratic Equation is a Polynomial Equation of 2nd Degree.However,this degree can increase to nth values.
Assumptions of Polynomial Regression:
•	The behavior of a dependent variable can be explained by a linear, or curvilinear, additive relationship between the dependent variable and a set of k independent variables (xi, i=1 to k).
•	The relationship between the dependent variable and any independent variable is linear or curvilinear (specifically polynomial).
•	The independent variables are independent of each other.
•	The errors are independent, normally distributed with mean zero and a constant variance (OLS).
Why do we need Polynomial Regression?
Let’s consider a case of Simple Linear Regression.
•	We make our model and find out that it performs very badly,
•	We observe between the actual value and the best fit line,which we predicted and it seems that the actual value has some kind of curve in the graph and our line is no where near to cutting the mean of the points.
•	This where polynomial Regression comes to the play.
•	Polynomial Regression is generally used when the points in the data are not captured by the Linear Regression Model and the Linear Regression fails in describing the best result clearly.
As we increase the degree in the model,it tends to increase the performance of the model.However,increasing the degrees of the model also increases the risk of over-fitting and under-fitting the data.
