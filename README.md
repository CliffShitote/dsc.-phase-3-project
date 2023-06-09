# Project phase 3 
![image](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/a7794ee7-fa45-4948-b59b-10596201f2db)

# Project Overview

The SyriaTel Customer Churn dataset is a collection of data that focuses on customer behavior and churn patterns in the telecommunications industry. 

# Business problem
 
 The business problem in the SyriaTel Customer Churn project is customer churn in the telecommunications industry. Churn refers to customers discontinuing services or switching to competitors, resulting in revenue loss and increased acquisition costs. The goal is to identify factors and patterns contributing to churn in SyriaTel. 
 
# The Data:

For this project, I will use a fictional dataset specifically created to simulate customer churn in a telecommunications company like SyriaTel. The dataset includes various features related to customer behavior, account information, and usage patterns. The dataset includes the following features (not an exhaustive list):

1.CustomerID: Unique identifier for each customer.

2.AccountLength: The length of time the customer has been with SyriaTel.

3.InternationalPlan: Whether the customer has an international calling plan or not.

4.VoiceMailPlan: Whether the customer has a voicemail plan or not.

5.NumberVmailMessages: The number of voicemail messages received by the customer.

6.TotalDayMinutes: Total number of minutes the customer used during the day.

7.TotalEveMinutes: Total number of minutes the customer used during the evening.

8.TotalNightMinutes: Total number of minutes the customer used during the night.

9.TotalIntlMinutes: Total number of international minutes used by the customer.

10.TotalDayCalls: Total number of calls made by the customer during the day.

11.TotalEveCalls: Total number of calls made by the customer during the evening.

12.TotalNightCalls: Total number of calls made by the customer during the night.

13.TotalIntlCalls: Total number of international calls made by the customer.

14.CustomerServiceCalls: Number of customer service calls made by the customer.

15.Churn: Binary indicator of whether the customer churned or not.

# Data Cleaning and EDA: 

Minimal data cleaning was required, however there was a need to manage missing values, duplicates, and outliers.

# Analysis of telecommunication providers ![Screenshot (443)](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/53ba0fc7-36b5-4aaa-bb43-6b7c35676690)
# Analysis numerical data  ![Screenshot (448)](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/c46d98c5-9426-491f-9a6c-c5e119b2f6ca)
# Features Correlation With Target Variables (churn)![Screenshot (449)](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/14ed1a43-e716-40c9-bbaa-907bb42b2774)
# Model results ![Screenshot (450)](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/da78b605-77c7-4b44-a2f2-cc26595fd82e)
# Comparing Models using ROC Curve Analysis ![Screenshot (451)](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/520c0ac3-446c-44f3-8eeb-5260912799a5)

# EVALUATION OF THE FINAL MODEL

Based on the provided classification report, here is the evaluation of the final model:

Accuracy: 94.2% Precision:

Class 0 (non-churned customers): 94% Class 1 (churned customers): 96% Recall (Sensitivity):

Class 0 (non-churned customers): 100% Class 1 (churned customers): 63% F1-score:

Class 0 (non-churned customers): 97% Class 1 (churned customers): 76% Support:

Class 0 (non-churned customers): 855 Class 1 (churned customers): 145 The accuracy of the model is 94.2%, indicating that it correctly predicts the churn status of 94.2% of the customers. Precision represents the proportion of correctly predicted positive instances out of the total predicted positive instances. In this case, the precision for class 0 (non-churned customers) is 94%, indicating that 94% of the predicted non-churned customers are actually non-churned. The precision for class 1 (churned customers) is 96%, indicating that 96% of the predicted churned customers are actually churned.

Recall, also known as sensitivity or true positive rate, represents the proportion of correctly predicted positive instances out of the total actual positive instances. The recall for class 0 (non-churned customers) is 100%, indicating that the model correctly identifies all the non-churned customers. The recall for class 1 (churned customers) is 63%, indicating that the model captures only 63% of the actual churned customers.

The F1-score is the harmonic mean of precision and recall. It provides a balanced measure between precision and recall. The F1-score for class 0 (non-churned customers) is 97%, indicating a good balance between precision and recall. The F1-score for class 1 (churned customers) is 76%, indicating that the model's performance in capturing churned customers is comparatively lower.

In summary, the final model achieves a high accuracy of 94.2%, with good precision and recall for class 0 (non-churned customers). However, the model's performance in identifying churned customers (class 1) could be further improved to increase the recall.

Please note that these evaluation metrics are based on the provided dataset and may vary when applied to new, unseen data. It is crucial to validate the model's performance on a separate test set or through cross-validation to ensure its generalizability.


# Conclusion: 

In conclusion, the analysis conducted to predict customer churn for SyriaTel, a telecommunications company, has provided valuable insights and recommendations to improve customer retention strategies. Through the modeling and evaluation process, a predictive model was developed to identify customers who are likely to churn. The analysis revealed that several factors contribute to customer churn in the telecom industry. By analyzing the dataset and building the predictive model, it was found that features such as call duration, customer complaints, billing issues, and contract type play a significant role in predicting churn. The model showed promising performance in accurately identifying potential churners.

# Recommendations:

![image](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/a4fbbe51-ce98-4f10-b58e-c19d29d15804)
