## House Prices Kaggle Competition
This is my second end to end project on [Kaggle](https://www.kaggle.com/c/titanic) 
using the House Prices Dataset.

This project is about predicting the price of a house with certain features using regression techniques.
Hence, this is a supervised regression problem.
There are several steps in building an end to end project. 
1. Data Preprocessing

When preprocessing the data, we can perform Feature Selection, Data Cleaning,
Feature Engineering, as well as Feature Scaling. There are no specific orders
of performing these steps, it depends on the dataset we are working with. In this dataset, we even performed a second Feature Selection to get rid of additional features.

2. Model Selection

In this step, I used several common regression models (e.g. Linear, Ridge, Lasso, Elastic, as well as Gradient Descent). We can compute the accuracy of each model to see which models gives the best accuracy using cross validation.

3. Test Set

Lastly, we can perform preprocessing on the test set as well as predict
the survival of each passenger using the best performing model.

**For a complete walkthrough of the project, check out the python notebook called 
house_prices_project.ipynb.**
