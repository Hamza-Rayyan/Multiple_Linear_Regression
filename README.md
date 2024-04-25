# Multiple_Linear_Regression
# Aim: To anticipate the future profits of a company based on their investments on certain aspects. 
- The Dataset contain attributes namely R&D, Administration, Marketing Spend, State.
# Steps: 
  - Importing the libraries.
  - Importing the dataset.
  - Encoding categorical data.
  - Splitting the dataset into the Training set and Test set.
  - Training the Multiple Linear Regression model on the Training set.
  - Predicting the Test set results
# Explaination:
  - First we will do our pre-processing steps on  data and make data ready for model.
  - As the dataset contain one attribute of string type which we have to convert into integer values or dummy variables for which we can use OneHotEncoder library to do so.
  - After that we take a variable in which we have stored our model LinearRegression(ie: regressor) and train both splitted sets namely X_train and y_train.
  - By making a new variable and testing a random dataset i.e X_test set and storing in that new variable we can compare it against the X_train set to find out the accuracy.

#Note : -Earlier we use to do Backward, Forward Elimination but the sklearn packages does it by itself so don't have to do it explicitely.
        -Further we can find the most weighted or influence of a particular independent variable using coefficients and intercepts methods to find out the weighted variable so that we can focus on that variable.
        
