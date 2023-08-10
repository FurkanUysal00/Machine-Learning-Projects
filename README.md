# Simple Linear Regression Model for Cereal Ratings
This repository contains a simple linear regression model implemented on the "cereal.csv" dataset. The goal of this project is to explore the relationship between the amount of sugars in cereals and their ratings, build a linear regression model using scikit-learn, visualize the relationship, and evaluate the model's performance using R-squared score and RMSE metrics.

# Dataset
The "cereal.csv" dataset contains information about various cereal brands and their nutritional attributes, including sugars and ratings.

Approach
# Exploratory Data Analysis (EDA): The dataset was first loaded and explored to understand its structure and attributes.

Data Visualization: A scatter plot was created to visualize the negative linear relationship between sugars and ratings. It was observed that cereals with higher sugar content tend to have lower ratings.

Model Implementation: A simple linear regression model was built using the scikit-learn library. The model was trained using the sugars feature as the independent variable and the rating feature as the dependent variable.

Model Visualization: The linear regression line was plotted on top of the scatter plot to visualize how well the model fits the data points.

Evaluation: The model's performance was evaluated using the R-squared score and RMSE. The R-squared score indicates the proportion of variance in the dependent variable (rating) explained by the independent variable (sugars). The RMSE measures the average prediction error of the model.

# Results
Negative Linear Relationship: The scatter plot showed a clear negative linear relationship between sugars and ratings in the cereal dataset.

Model Performance: The R-squared score was calculated to be approximately 0.52, indicating that 52% of the variance in ratings can be explained by the variance in sugars. The RMSE was calculated to be approximately 0.12, reflecting the average prediction error of the model.

Conclusion
The implementation of a simple linear regression model on the "cereal.csv" dataset demonstrated a negative linear relationship between sugars and ratings. The model's performance was evaluated using R-squared score and RMSE, providing insights into how well the model fits the data and makes predictions.
