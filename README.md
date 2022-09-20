# Moped Fake Review Identification with Machine Learning

## Project Description
- Accurately identify moped reviews left by people that have never actually owned one
- EMO, the motorcycle manufacturer, obtained some review data where they know that a reviewer did not own the moped
- Use the available features given in each review (Visual Appeal, Reliability, Comfort rating etc.) to identify patterns that could point to whether a review comes from a non-moped owner or not.
- Goes through the process of Data Validation, Exploratory Analysis, Model Fitting, and Model Evaluation to determine the most viable Machine Learning method

## Results
- Decision Tree ML model gives us a slightly better accuracy score than the Logistic Regression model
- However, given the nature of the business problem, it would be more prudent to choose the ML algorithm which gives the higher percentage of True Negatives
- We decide to move forward with the Logistic Regression model, given it accurately identified a greater number of false reviews than the Decision Tree model