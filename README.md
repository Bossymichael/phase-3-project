# <h1 style="text-align: center;">TELECOMMUNICATION COMPANIES:SYRIATEL CUSTOMER CHURN </h1>
 ![alt text](telecom.jpg)




## Project Overview
Telecommunication companies face increasing challenges in retaining customers due to market competition and changing consumer preferences. By analyzing customer data, such as demographics, service usage, contract type, and payment methods, these companies aim to identify patterns associated with churn. Understanding these patterns allows telecom providers to develop targeted strategies to reduce churn rates, enhance customer satisfaction, and optimize service offerings, ultimately driving sustainable growth and maintaining a competitive advantage in the dynamic telecom industry.

## Business Understanding

### Problem Statement
Telecommunications companies face substantial revenue loss from high customer churn rates. Without understanding the factors driving churn through customer behavior and service data, they struggle to implement effective retention strategies, leading to higher acquisition costs and reduced profitability.

##  Objectives
### Main Objectives
To identify predictable patterns in customer behavior and service usage that indicate a higher likelihood of churn, enabling Syriatel to implement targeted strategies for customer retention and reduce revenue loss from customer attrition

###  Specific Objectives
Identify and segment customers who are most likely to churn based on their usage patterns, service history, and engagement levels
Determine the key drivers of customer dissatisfaction by analyzing customer service interactions, complaints, and feedback, and develop initiatives to improve overall service quality and satisfaction.
come up with strategies that will reduce customer's service calls by addressing common issues affecting their customers
Develop machine learning models that will predict wether a customer will churn or not

### Success Metrics
Accuracy – The proportion of correctly predicting wether a customer will churn or not 85% - 90%

Precision - 80%.

Recall - 80-90%

###  StakeHolders
Customers: The primary stakeholders whose behavior and satisfaction directly impact churn rates

Marketing Team: Responsible for developing and implementing strategies to attract and retain customers

Finance Team: Monitors the financial impact of churn on revenue and profitability

Customer Service Team: Handles customer interactions and support


### Constraints
Choosing the Right Metrics: Different stakeholders may prefer different evaluation metrics (e.g., accuracy, precision, recall, F1-score, AUC-ROC). Balancing these can be tricky, especially with imbalanced data.

The churn column has class imbalance that might affect the modelling process where the models learn so well on the majority class than the minority class

##  Modelling
Processes I will use in the modelling process:

Data Preprocessing: One hot encoding and label encoding and scaling the data

I will do train test split where I will split the adta into train an test size where the test size is 0.2.

I will start with the baseline models


### Conclusion

Logistic Regression has the highest ROC AUC score of 0.82.
Random Forest and Gradient Boosting have the highest Accuracy of 0.76.
Although Random Forest and Gradient Boosting have higher accuracy than Logistic Regression, their ROC AUC scores are slightly lower (0.81 and 0.80), respectively

The Logistic Regression model is the best model according to the ROC AUC score of 0.82, indicating better performance in distinguishing between classes. The Random Forest model is a strong contender based on Accuracy and has a relatively high ROC AUC score, making it a good choice as well. However, if prioritizing the model's ability to differentiate between classes is key, Logistic Regression would be the best choice.

### Recommendations

 Regularly review and optimize pricing strategies to ensure competitiveness. Consider implementing tiered pricing models to cater to different customer segments.

 Use clustering techniques such as K-Means, hierarchical clustering, or DBSCAN to segment customers into distinct groups based on key features like service usage (e.g., data, SMS, and call volume), tenure, payment history, and engagement levels.

 Continuously track customer usage patterns and flag sudden changes (e.g., significant drop in data usage or calls).

 Create a comprehensive FAQ section and knowledge base addressing the most common queries and issues raised by customers.

  - Regularly review and optimize pricing strategies to ensure competitiveness. Consider implementing tiered pricing models to cater to different customer segments.
 - Use clustering techniques such as K-Means, hierarchical clustering, or DBSCAN to segment customers into distinct groups based on key features like service usage (e.g., data, SMS, and call volume), tenure, payment history, and engagement levels.
 - Continuously track customer usage patterns and flag sudden changes (e.g., significant drop in data usage or calls).

- Create a comprehensive FAQ section and knowledge base addressing the most common queries and issues raised by customers.

- Continuously monitor model performance and retrain models with new data to ensure they remain accurate and relevant

- Implement technologies like AI-powered chatbots and automated systems to streamline customer interactions.

- Implement technologies like AI-powered chatbots and automated systems to streamline customer interactions.

- Reward loyal customers with exclusive discounts, benefits, and perks.


# Nexts Steps

 Conduct Sentiment Analysis on Customer Feedback: Utilize Natural Language Processing (NLP) techniques to analyze customer service interactions, complaints, and feedback. Identify common negative sentiments and pain points that customers express.

 - Develop an automated pipeline for model deployment to allow real-time or batch prediction of churn risk.

 - Implement a system for real-time alerts or dashboards to notify the retention team of high-risk customers based on model predictions

  - Continuously monitor model performance using key metrics and regularly retrain models with new data to ensure they stay accurate and relevant.
















