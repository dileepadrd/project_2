# Analysis of Ease of Doing Business Rankings: Identifying Top Performing Countries and Predicting Future Rankings using Linear Regression



## Question: Which country has shown the most improvement in their Ease of Doing Business ranking in the past 5 years?

## Project Overview
This code is written in Python and uses several libraries to analyze the Ease of Doing Business dataset. The code aims to find the top 20 countries with the highest average Ease of Doing Business ranking and visualize a linear regression model that predicts the Ease of Doing Business ranking for the year 2019 based on the average ranking for the past 5 years. Finally, the code calculates the mean squared error and R-squared score for the model.

## Dataset
The Ease of Doing Business dataset is used in this code. The dataset is available in the ease-of-doing-business.csv file. The dataset contains information about the Ease of Doing Business ranking for different countries from the year 2004 to 2019.

## Analysis
The code reads the Ease of Doing Business dataset and drops any missing values. It then calculates the average Ease of Doing Business ranking for the past 5 years and selects the top 20 countries based on their average ranking. The code then corrects the country names and creates a new dataframe with the top 20 countries and their ranks.

Next, the code splits the data into training and testing sets and trains a linear regression model using the training data. The model is then used to predict the Ease of Doing Business ranking for the year 2019 based on the average ranking for the past 5 years. The code visualizes the linear regression model and saves the image as linear_regression_model.png. Finally, the code calculates the mean squared error and R-squared score for the model.

## Result
The code outputs the top 20 countries with the highest average Ease of Doing Business ranking and the mean squared error and R-squared score for the linear regression model. The code answers the question, "Which country has shown the most improvement in their Ease of Doing Business ranking in the past 5 years?" but does not provide a direct answer to it.


​


