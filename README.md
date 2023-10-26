# Improving-employee-retention-in-Salifort-Motors
Salifort Motors seeks to improve their employees retention, what's likely to make the employee leave the company?

## Overview 

The goal of this project was to create a Logistic Regression, Decision Tree and Random Forest models to predict of a employee will leave the company or not. This project utilized a "Salifort Motors" company dataset.
The Logistic Regression model performed with 82% accuracy, 45% precision, 25% recall and F1 score of 32%.
The Random Forest model outperformed both of Logistic and Decision Tree models with a performance of 98% accuracy, 99% precision, 91% recall and F1 of 95%, both of Decision Tree and Random Forest models determined what features were the most important and both had the same most important features.
Based of the tree based models, the satisfaction level, tenure, number_project, last evaluation and average monthly hours were the most influential in predicting whether the employee gonna leave or not.

## Business Understanding 

Salifort Motors faces a critical challenge of employee retention. High employee turnover can result in increased recruitment and training costs, as well as disruption in operations. To address this issue, the company is seeking to predict which employees are likely to leave the organization and understand the factors that contribute to employee attrition. By identifying the root causes and patterns associated with employee departures, Salifort Motors aims to implement proactive measures to improve retention rates, reduce costs, and maintain a more stable and satisfied workforce.

This project is designed to provide data-driven insights and predictive models to support Salifort Motors in making informed decisions related to employee retention and engagement strategies.

## Data Understanding 

This project uses a dataset called "HR_capstone_dataset.csv". It represents 10 columns of self-reported information from employees of a fictitious multinational vehicle manufacturing corporation.
The dataset can be found on [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction)

## Modeling and Evaluation 

A Random Forest model was used to determine feature importance in who would leave or not. The below plot shows the most important factors in determining if a employee would leave or not.


Also a Decision Tree model was used to determine the feature importance, the plot below shows the Decision Tree features chosen.

## Conclusion

Those models helps predict whether an employee will leave and identify which factors are most influential. These insights can help human resources make decisions to improve employee retention.
