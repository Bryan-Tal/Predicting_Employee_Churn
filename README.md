# Providing_Data_Driven_Suggestions
Providing Data Driven Suggestions for HR

## Project Overview
The goal of this project was to create a decision tree, random forest model, and XGBoost model to employee turnover. This project utilized data collected by the HR department. The final Random Forest model performed with 98.2% accuracy and 98.3% precision. Based on the model, the satisfaction level, average monthly hours worked, and previous evaluation score were the three most influential features in determining whether or not an employee will leave.

## Business Understanding
Predicting which employees are likely to quit can significantly benefit the company by reducing the time and costs associated with the recruitment process. Early identification of potential turnover enables HR to implement targeted strategies to improve employee retention, ensuring the organization can maintain productivity and focus on critical projects.

## Data Understanding
The HR Analytics Dataset came from [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv). The data consisted of approximately 15,000 employees and 10 features. The features included information on employee satisfaction level, their last evaluation score, the number of projects they contribute to, the average hours worked per month, as well as other features. 

## Modeling and Evaluation
A Random Forest model comprising 100 decision trees was the champion model used to determine feature importance in who leave the company. 

![image](https://github.com/user-attachments/assets/84d496c7-622b-4f78-93b6-0c9caf2362c5)

The below plot shows that satisfaction_level, average_monthly_hours, and last_evaluation were the Top 3 most important factors in determining employee turnover. The overall model performed with 98.2% accuracy and 98.3% precision. ![image](https://github.com/user-attachments/assets/4182e402-c29c-4a1c-97ef-9dede1afe3fa)


## Conclusion
The predictive models developed in this project demonstrated the potential to significantly enhance HR decision-making by identifying employees at risk of leaving with high accuracy and precision. The Random Forest model, achieving 98.2% accuracy and 98.3% precision, proved to be the most effective in determining key factors influencing employee turnover, such as satisfaction level, average monthly hours, and last evaluation score. These insights can help HR teams proactively address retention challenges, optimize workforce strategies, and foster a more stable and engaged workplace. Future efforts could focus on incorporating additional data sources and refining the model to address unique organizational contexts, further enhancing its utility.
