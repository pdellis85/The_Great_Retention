# The Great Retention

Consulting for a Multinational Corporation about their HR Data and Employee Retention Strategy.


## Project Proposal

> For our project we will try to create predictions to see if an employee will stay or leave a company. We'll fit several algorithm models (see list below) to HR data to create a predictive model as well as plot the top 5 employee importance feature graph.

## Finding Data

We decided to use MNC company HR data from Kaggle. 
https://www.kaggle.com/kmldas/hr-employee-data-descriptive-analytics


## Data Preparation & Model Training

1. Change the percentage data to decimal format
2. Dropped the emp ID column

We used Jupyter lab and AWS SageMaker to prepare a training and testing dataset and to train the machine-learning models.

Here are the columns within the HR data:

* Emp_Id: Id of Employee.
* satisfaction_level: Satisfaction level of employee in percentage. 100% or 1 is very satisfied. 0% or 0 is not satisfied.
* last_evaluation: Time from last evaluation in years.
* number_project: Number of projects an employee is working on.
* average_montly_hours: Average hours worked by employees in the last 3 months.
* time_spend_company: Time spent by my employee commuting to the office.
* Work_accident: If the employee was involved in a work accident.
* left: If the employee has left the company.
* promotion_last_5years: If the employee has a promotion in the past 5 years.
* Department: Department employee is working in.
* Salary: Salary Range from low to high


Our Target value for training all the models was the "left" column

## Model Evaluation

Use the testing data to evaluate 7 models to see which model would be the best model to use for our predictions and graphs. 

We used the following models:
* Logistic Regression Model
* Decision Tree Model
* Gradient Boosted Tree Model
* Random Forest Model
* Gaussian Naive Bayes Model
* Support Vector Machines
* XGBOOST Model

## Predictions and Conclusions

The summarization, conclusion and predictions can be found in the PDF presentation below.


## Presentation

* https://docs.google.com/presentation/d/14WocU3Hvgyt79hxfmT5bdSjsQbcBTe218ilCIrmqbKo/edit?usp=sharing
