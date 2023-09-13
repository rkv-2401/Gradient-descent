# Gradient-descent
Implementing Ridge and Stochastic Gradient Descent from scratch as practice for Machine Learning.

CarSeats.csv is the data file, consisting of 400 observations describing the child car seats for sale at 400 stores.

I perform standard scaling, centering the target variable, and first compute the Beta value manually and ascertain that it matches with the Beta value computed by Scikit Learn's Ridge module.

Then, I create the ridge regressor function by hand. I allow it to iterate with various step sizes to see how the value of B-pred changes over time and determine the best step size for this dataset.
