# HouseSales_KingCounty
This is the final assignment of the "Data Analysis with Python" course offered by IBM on Coursera.

In this notebook, I analysed and predicted housing prices using attributes or features such as square footage, number of bedrooms, number of floors and so on.
To complete this assignment, I was asked to answer the following questions:
  1- Display the data types of each column using the attribute dtypes
  2- Drop the columns "id" and "Unnamed: 0" from axis 1 using the method drop(), then use the method describe() to obtain a statistical summary of the data.
  3- Use the method value_counts to count the number of houses with unique floor values, use the method .to_frame() to convert it to a dataframe.
  4- Use the function boxplot to determine whether houses with a waterfront view or without a waterfront view have more price outliers.
  5- Use the function regplot in the seaborn library to determine if the feature sqft_above is negatively or positively correlated with price.
  6- Fit a linear regression model to predict the price using the feature 'sqft_living' then calculate the R^2.
  7- Fit a linear regression model to predict the 'price' using the list of features.
  8- Create a pipeline object that scales the data performs a polynomial transform and fits a linear regression model. Fit the object using the features in the question above, then fit the model and calculate the R^2.
  9- Create and fit a Ridge regression object using the training data, setting the regularization parameter to 0.1 and calculate the R^2 using the test data.
  10- Perform a second order polynomial transform on both the training data and testing data. Create and fit a Ridge regression object using the training data, setting the regularisation parameter to 0.1. Calculate the R^2 utilising the test data provided. 
