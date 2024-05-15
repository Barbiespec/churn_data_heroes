# Churn_data_heroes
## Introduction
The financial services industry's ecosystem is dynamic and multidimensional, characterized by a complex interplay of factors that influence consumer behaviors. In this complex environment, the ability to retain customers is more than a strategic advantage; it is a requirement for long-term growth and sustainability. The inherent challenges of customer attrition for financial institutions include substantial revenue loss and the erosion of brand loyalty.
## Problem statement
- Give a clear understanding of customer demographics, behaviors, and churn patterns 
- Identify key features influencing customer churn. 
- Provide strategic recommendations for the bank based on data-driven insights.
 ## Data sourcing
The churn database was provided by a bank in Canada containing information on 10,000 bank customers over six months. 
## Data transformation and cleaning 
To make our dataset suitable for analysis, we need to clean and transform dataset by:
- creating a new conditional credit score column where credit score of 0-499 is very poor, 500-600 is poor, 601-660 is fair, 661-780 id good and 781-850 is excellent
- adding a new column titled "age_grade" and categorizing individuals aged 18-30 as young, 31-60 as advanced, and 61 and above as old 
- creating a new column titled "tenure_stay" for customers that has been with the bank for 0-5 years as short stay and 6-10 as long stay
- adding a new column titlled "estimated_salary" and categorizing individuals salary from 0-66575 as lower class, 66576-133150 as middle class, 131151-199725 as first class
- creating a new column titled "churned_" where those that churn is "yes" and those that did not churn is "no"
