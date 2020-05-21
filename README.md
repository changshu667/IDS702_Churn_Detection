# IDS702_Churn_Detection

# Background
Attrition in HR:
A major problem of high employee attrition is its cost to an organization. Job postings, hiring processes, paperwork and new hire training are some of the common expenses of losing employees and replacing them. Management department of an organization always wants to figure out what factors influence employees' attrition, in this way they could work out better strategy to retain excellent employees.


# Questions
> Main Questions:
Is there evidence that employees who have worse work life balance tend to have higher probability to leave their company? 
Is there evidence that the effects differ by job level? 
Is there evidence that the effects differ by job role? 

> Other questions of interest:
What are other important predictors lead to employees' attrition?
How is the attrition rate in different job roles or different job levels? 


# Dataset
This is a fictional dataset provided by IBM data scientists.
1470 rows, 35 variables
Samples of Variables: Age, Education, Education Field, Job level, Job Role, Environmental Satisfaction, Job satisfaction, MonthlyIncome, Percent of Salary Hike

# Variables
### Personal Information 
Age, Gender, Education, Education Field, Marital Status, Total working years
### Job Role Related
Department, Job level, Job Role, Year at company, Number of companies worked, Business travel, Distance from home, Over Time, Work life balance, 
### Subjective feeling 
Environmental Satisfaction, Job satisfaction, Relation satisfaction, 
### Others' evaluation
Job Involvement, Performance Rating
### Income
DailyRate, MonthlyRate, MonthlyIncome, Percent Salary Hike, Stock option level, 
### Career development
Training time last year, Year in current role, Years since last promotion, Years with current manager

# Limitation
1. For outcome variable, the "attrition" one is not balanced. 16.1% of the datapoint correspond to "Yes" and 83.9% of the datapoint correspond to "No".
2. Since the dataset just contains 1470 cases, there are some unbalanced groups in our dataset (For performance rating: only 15.1% of employees received score 4, And for employees??? department,  65.4% comes from Research&Development Department ). This would cause harm to a classification model like logistic regression. If we could collect more data, we will do better on capturing sufficient patterns of subsets.
