# Titanic_Survival_prediction_using_Linear_regression
 Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

The Software used are Jupyter Notebook and Python<br>
Library Used are Sklearn, Numpy, and Pandas.

We use Linear Regression to Predict which passenger might have survived the shipwreck and while doing so the 
features we have considered are -: Age,Sex,Fare and Pclass.

*One problem with Sex is that the original data contained 'Male' and 'Female' as the  possible value. I changed 
it to 1 for male and 0 for female.*

In linear regression, we use multiple features to create a linear model that best fits the data for prediction.

The equation for linear regression generally looks like <br>
  *survival = w1 x Age + w2 x Sex + w3 x Fare + w4 x Pclass + b* <br>
In linear regression we find the proper weights for the w1 w2 w3 w4 and b using the gradient descent.
Then using this weights we predict the possible value.

Accuracy Achieved :- 0.76


