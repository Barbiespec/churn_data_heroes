# Churn_data_heroes
<img width="333" alt="Screenshot 2024-05-15 155327" src="https://github.com/Barbiespec/churn_data_heroes/assets/158063327/988e43ee-f1bf-44fa-9e5c-4456dac490f9">

## Introduction
The financial services industry's ecosystem is dynamic and multidimensional, characterized by a complex interplay of factors that influence consumer behaviors. In this complex environment, the ability to retain customers is more than a strategic advantage; it is a requirement for long-term growth and sustainability. The inherent challenges of customer attrition for financial institutions include substantial revenue loss and the erosion of brand loyalty.

## Problem statement
- Give a clear understanding of customer demographics, behaviors, and churn patterns 
- Identify key features influencing customer churn. 
- Provide strategic recommendations for the bank based on data-driven insights.

 ## Data sourcing
The churn database was provided by a bank in Canada containing information on 10,000 bank customers over six months. 

## Files 
- Churn_data Heroes.pbix: Contains dataset used for transformation and visualization
- Data_Dictionary.gd: Documentation describing the structure and contents of each table in the dataset.
- dashboard: provide valuable insight as to the factors influencing customer churn
- README.md: This file, provides an overview of the repository and instructions for transforming and visualizing data

Click 👉 [here](https://drive.google.com/drive/folders/1Dv3KHHDefV7-OlzdBe15KhS3redqZ_gE?usp=sharing) 👈to see these files.

## Data transformation and cleaning 
To make our dataset suitable for analysis, we need to clean and transform dataset by:
- Creating a new conditional credit score column where credit score of 0-499 is very poor, 500-600 is poor, 601-660 is fair, 661-780 id good and 781-850 is excellent
- Adding a new column titled "age_grade" and categorizing individuals aged 18-30 as young, 31-60 as advanced, and 61 and above as old 
- Creating a new column titled "tenure_stay" for customers that has been with the bank for 0-5 years as short stay and 6-10 as long stay
- Adding a new column titlled "estimated_salary" and categorizing individuals salary from 0-66575 as lower class, 66576-133150 as middle class, 131151-199725 as first class
- Creating a new column titled "churned_" where those that churn is "yes" and those that did not churn is "no"

   ## Dataset before cleaning and transformation
  <img width="944" alt="Screenshot 2024-05-15 155528" src="https://github.com/Barbiespec/churn_data_heroes/assets/158063327/68dbb4e3-183a-41fb-a948-bdc1af2a89e3">

  ## Dataset after cleaning and transformation
 The datasets are now suitable for analysis and easy visualisation after cleaning and transforming the dataset
 <img width="620" alt="Screenshot 2024-05-15 160420" src="https://github.com/Barbiespec/churn_data_heroes/assets/158063327/e9100b7e-d6a3-45a2-844b-f367122fb7e6">

 ## Dax
 The formula language was used to calculate
 - The total number of people that churned
 - The distinctive count of  total number of customers
 - The churn rate
 ## Dashboard visualization 
 This provide valuable insight as to the factors influencing customer churn based on various demographic and banking behavior attributes.
 
<img width="488" alt="Screenshot 2024-05-16 202730" src="https://github.com/Barbiespec/churn_data_heroes/assets/158063327/b3a1a4cc-7546-4faa-9557-7aacf3ee7409">


## Recommendation

 **Segmentation Analysis**: this helps understand the characteristics and behaviors of churned customers, that were Grouped based on various attributes such as credit score ranges, tenure with the bank, geographical locations, demographics. A predictive model was developed to forecast customers that likely churned and the reason why they churned. customers with low credit score, short stay tenure with the bank, diatance from the bank churned more. other features that influence customer churn are age_grade, gender, and social class. After understanding customer behaviour the following ideas are recommended:

 **Credit Score Improvement Programs**: Collaborate with the bank's credit department to design programs aimed at improving customers' credit scores. Provide personalized financial advice, credit education materials, and incentives for credit score improvement.

 **Customer Engagement Strategies**: Implement targeted customer engagement strategies based on segmentation analysis findings. Offer personalized promotions, discounts, or loyalty programs to incentivize longer-term relationships with the bank.

 **Geographical Expansion**: Evaluate the feasibility of expanding the bank's physical presence or enhancing digital banking services in areas where customers are geographically distant. Consider partnerships with local businesses or fintech companies to improve accessibility for remote customers.

 **Customer Feedback Analysis**: Analyze feedback from churned customers to identify common pain points and areas for improvement. Use sentiment analysis and natural language processing techniques to extract valuable insights from customer comments and reviews.

 **Retention Campaigns**: Launch retention campaigns tailored to specific customer segments identified as high-risk for churn. Offer personalized retention offers, such as fee waivers, interest rate reductions, or exclusive banking services, to incentivize customers to stay with the bank.

 **Continuous Monitoring and Evaluation**: Regularly monitor the effectiveness of implemented strategies using key performance indicators (KPIs) such as churn rate, customer satisfaction scores, and retention rates. Adjust tactics as needed based on ongoing analysis and feedback.

By implementing these recommendations, the bank can leverage data-driven insights to mitigate churn, improve customer retention, and foster long-term relationships with its clientele.

## Author
[Rosemary ihemeje](https://www.linkedin.com/public-profile/settings?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_self_edit_contact-info%3B202xL14xR76Trgbi2YEolw%3D%3D)

## License
This project is licensed under the Datafied Technologies License - see the LICENSE file for details.
