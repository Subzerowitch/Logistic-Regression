# Logistic-Regression

**Project Title**

  Predicting #cakeweek using Logistic Regression

**Introduction**

  This project aims to predict whether a recipe was part of #cakeweek based on other recipe features. The dataset used for this analysis is sourced from Kaggle. The main focus is on using logistic regression as the predictive model to classify recipes.

**Dataset Description**
  
  The dataset contains recipes with various features, and we are particularly interested in predicting the #cakeweek column, which has binary values (1.0 or 0.0). Before proceeding with the logistic regression, we first filter the dataset to contain only rows where #cakeweek is 1.0 to explore potential correlations with other columns.

**Exploratory Data Analysis**

  In this section, we conduct exploratory data analysis on the filtered dataset to identify any correlations or patterns between the #cakeweek column and other features such as 'bake', 'tree nut free', and 'vegetarian'.

**Data Preprocessing**

  Before training the logistic regression model, we perform data preprocessing steps such as handling missing values and encoding categorical variables. Scaling or normalization might also be applied depending on the requirements of the model.

**Logistic Regression Model**

  In this section, we build the logistic regression model to predict #cakeweek based on the selected features ('bake', 'tree nut free', and 'vegetarian'). We split the dataset into training and testing sets using the train_test_split function from Scikit-learn.

**Model Evaluation**

  After training the logistic regression model, we make predictions on the test set and evaluate its performance using accuracy as the primary metric. Additionally, we create a modified version of predictions by applying a specific condition to improve model accuracy based on our domain knowledge.

**Results and Conclusion**

  We present the results of the logistic regression analysis, including accuracy scores for both the original and modified predictions. We interpret the performance of the model and discuss its ability to predict #cakeweek based on the provided features.

