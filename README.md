# Polynomial-Regression-Salary-Prediction-Python  

**Introduction**  

In this project, we explore polynomial regression to predict salaries based on position levels. We use a dataset containing position levels and corresponding salaries to train our model. The goal is to compare the performance of linear regression and polynomial regression in this predictive task.

**Dataset**  

The dataset used in this project is named Position_Salaries.csv. It includes two columns:  


**Position Level:** Numerical values representing the position levels.  

**Salary:** Corresponding salary for each position level.  

We load and preprocess the dataset using pandas to extract features (x) and target variable (y).

**Methodology**  

Data Preprocessing: We split the dataset into features (x) and the target variable (y). We then split the data into training and testing sets using the train_test_split function from sklearn.model_selection.  


**Linear Regression:** We train a linear regression model to predict salaries based on position levels. We visualize the results using matplotlib.  


**Polynomial Regression:** We utilize polynomial features to transform the input data and then train a linear regression model on the transformed features. This allows us to capture non-linear relationships between features and the target variable.  


**Visualization:** We plot the predictions of both linear regression and polynomial regression models to compare their performance.  


**Results**
**Linear Regression:** The linear regression model yields a straight line fit to the data. However, it fails to capture the non-linear relationship between position levels and salaries.  


**Polynomial Regression:** The polynomial regression model provides a more flexible fit to the data. By introducing polynomial features, we capture the curvature in the relationship between position levels and salaries.  


**Conclusion**  

In this project, we demonstrated the application of polynomial regression for predicting salaries based on position levels. We compared the performance of linear regression and polynomial regression models, highlighting the importance of capturing non-linear relationships in predictive tasks.
