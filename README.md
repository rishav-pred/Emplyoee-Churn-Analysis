# Emplyoee-Churn-Analyis
The dataset contains 10 columns and 14,999 rows. Here's a brief overview of the columns:

satisfaction_level: Employee satisfaction level (float).
last_evaluation: Last evaluation score (float).
number_project: Number of projects (integer).
average_montly_hours: Average monthly hours (integer).
time_spend_company: Time spent at the company (integer).
Work_accident: Whether the employee had a work accident (integer, 0 or 1).
left: Whether the employee left the company (integer, 0 or 1).
promotion_last_5years: Whether the employee was promoted in the last 5 years (integer, 0 or 1).
Department: Department (categorical).
salary: Salary level (categorical).
Next, we'll preprocess the data, encode the categorical variables, and split the dataset into training and testing sets. Then, we will train a machine learning model to predict whether an employee will leave the company or not.

Random Forest achieved the highest accuracy at 98.83%, with excellent precision and recall for both classes.
Logistic Regression had lower accuracy and struggled with the recall for class 1 (employees who left).
