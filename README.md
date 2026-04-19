
### In this project, I perform EDA and cleaning on cars data and compute linear regression to predict the car prices. 

## Statistical Analysis
1. Computed skewness and z-score to understand the outliers. 
2. Computing correlations and understanding postitive vs negative correlations, to understand which fators show a linear relation with the target variable
   and how different independent variables are related to each other to understand if there exists multicollinearity.
3. Explored Variance Inflation Factor to understand how to reduce multicollinearity in order to perform a regression to get most accurate results
4. Used Seaborn to plot scatter and variance plots.

## Data Cleaning
1. Cleaned the data to get rid of missing values, corrected misinformation, created new columns to store data.
2. Treating outliers by IQR (Interquartile range method). In this method we adjust the values of all the data point that lie below lower quartile
   (below 25% quartile) and the data points that liw above upper quartile (above 75% quartile)

## Data Preparation
1. Creating x and y sets of data
2. Computing VIF to check for multicollinearity
3. Using Principal Component Analysis to correct the multicollinearity found with the VIF method, so that the correlation between different independent
   interfere with the model bulding process.

## Model Computation
1. In the results, p values indicate the presence of multicollinearity
2. Compared train and test accuracy, train and test error, and mean squared error and adjusted mean sqaured error.

