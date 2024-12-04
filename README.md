The employee attrition project was performed using the XGBoost model
# Project Title: Predictive modeling of Employee Attrition

# Description
This project was completed as part of the Google Advanced Analytics Course offered through Coursera.
The aim of the analysis was to predict whether an employee would leave the company based on a set of variables asscoiated with employee performance, workload, salary and satisfaction etc.

I chose to use the XGBoost model as it requires relatively few data assumptions and is robust with collinear data.

# Table of Contents

- [Project Title](#project-title)
- [Description](#description)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Dataset](#dataset)
- [Development](#development)
- [Contribute](#contribute)
- [License](#license)

# Installation
The modeling uses the `HR_capstone_dataset.csv` file.  
The dataset can also be found on [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv) or [here](https://github.com/phildonaldson1/Employee_Attrition_XGBoost_model/blob/main/data/HR_capstone_dataset.csv) 
[(Back to top)](#table-of-contents)

# Dataset
[(Back to top)](#dataset)
The dataset contains:

14,999 rows – each row is a different employee’s self-reported information

10 columns

|Column name          |Type  |Description                                            |
|---------------------|------|-------------------------------------------------------|
|satisfaction_level   |int64 |The employee’s self-reported satisfaction level [0-1]  |
|last_evaluation      |int64 |Score of employee's last performance review [0–1]      |
|number_project       |int64 |Number of projects employee contributes to             |
|average_monthly_hours|int64 |Average number of hours employee worked per month      |
|time_spend_company   |int64 |How long the employee has been with the company (years)|
|work_accident        |int64 |Whether or not the employee experienced an accident while at work|
|left                 |int64 |Whether or not the employee left the company           |
|promotion_last_5years|int64 |Whether or not the employee was promoted in the last 5 years|
|department           |str   |The employee's department                              |
|salary               |str   |The employee's salary (low, medium, or high)           |



# Development
The data 
[(Back to top)](#table-of-contents)

# Contribute
[(Back to top)](#table-of-contents)

# License
[(Back to top)](#table-of-contents)
