# Used-Car-Price-Prediction

There is a need for a system in which the price of a certain used car can be determined by analyzing a variety of features. These features are very crucial in determining the best possible price for the used car in particular.

In this project, I will use a data set of 100.000 used vehicles information of 9 different brands. I will first import the packages those are relevant in this project.

LinearRegression, RandomForestRegression, DecisionTreeRegressor, Logistic Regression, Lasso Regressor models are used with the metrics.

General Information about the Data

Data Wrangling of Categorical Variables

Data Wrangling of Numerical Variables

Exploratory Data Analysis of Categorical Variables

Analysing Relationships Between Numerical Variables

Analysing the Distribution of Numerical Variables

Data Processing

Creating Dummy Variables

Hypothesis Testing

The pvalue in both calculations are lower than 0.05. It appears that there is a difference between how much is the price of automatic vehicles versus how much non-automatic vehicles prices.

As a result, our hypothesis testing result is we are going to reject null hypothesis and accept the alternative one.

Preprocessing and Training Data Development

a.Creating Training and Test Sets

b.Scaling The Data

c.Modeling

  1. DecisionTreeRegressor
  2. Ridge
  3. LinearRegression
  4. RandomForest
  5. LassoLinearRegression

d. Metrics

  1. R-Square
  
  2. Root_Mean_Squared_Error
  
  3. Average 5-Fold CV Score
  
Results

We notice that our scaled random forest regressor is able to explain the most variance (93%)within the price of used cars in comaprison to the other models built using the scaled data. We also have the lowest root mean squared error (£1234) as a result of using this model.

