Predicting SyriaTel Customer Churn![image](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/2dc22c2a-4921-4781-9e34-3d382655d007)
![image](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/a7794ee7-fa45-4948-b59b-10596201f2db)
Project Overview:
The SyriaTel Customer Churn dataset is a collection of data that focuses on customer behavior and churn patterns in the telecommunications industry. ![image](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/838f30fe-2ead-454a-bcfc-3d407078858b)
Business Problem: The business problem in the SyriaTel Customer Churn project is customer churn in the telecommunications industry. Churn refers to customers discontinuing services or switching to competitors, resulting in revenue loss and increased acquisition costs. ![image](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/8b7f3898-b13f-4070-9cbc-5d71e1e7545e)
The Data: For this project, I will use a fictional dataset specifically created to simulate customer churn in a telecommunications company like SyriaTel. The dataset includes various features related to customer behavior, account information, and usage patterns. The dataset includes the following features (not an exhaustive list):
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
Data Cleaning and EDA: Minimal data cleaning was required, however there was a need to manage missing values, duplicates, and outliers.
ANAYSIS OF TELECOMMUNICATION PROVIDERS ![Screenshot (443)](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/53ba0fc7-36b5-4aaa-bb43-6b7c35676690)
Analysis numerical data  ![Screenshot (448)](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/c46d98c5-9426-491f-9a6c-c5e119b2f6ca)
FEATURES CORRELATION WITH TARGET VARIABLES (churn)![Screenshot (449)](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/14ed1a43-e716-40c9-bbaa-907bb42b2774)
MODEL RESULTS ![Screenshot (450)](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/da78b605-77c7-4b44-a2f2-cc26595fd82e)
Comparing Models using ROC Curve Analysis ![Screenshot (451)](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/520c0ac3-446c-44f3-8eeb-5260912799a5)
Based on the ROC-AUC scores comparison of the 4 machine learning models, it can be concluded that the Random Forest model performed the best. Therefore, this model will be chosen to make predictions on new data in the future.
Conclusion: In conclusion, the analysis conducted to predict customer churn for SyriaTel, a telecommunications company, has provided valuable insights and recommendations to improve customer retention strategies. Through the modeling and evaluation process, a predictive model was developed to identify customers who are likely to churn. The analysis revealed that several factors contribute to customer churn in the telecom industry. By analyzing the dataset and building the predictive model, it was found that features such as call duration, customer complaints, billing issues, and contract type play a significant role in predicting churn. The model showed promising performance in accurately identifying potential churners.
![image](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/d2f3b9bf-800e-4e64-9f04-fc51defe3631)
Recommendations:

Enhance customer satisfaction and address complaints promptly.
Offer incentives for long-term contracts to promote customer loyalty.
Proactively reach out to customers to address concerns and provide support.
Design targeted marketing campaigns to engage and retain high-risk customers.
Continuously improve product and service offerings based on market trends and feedback.
Provide exceptional customer service and empower customer service representatives.
Monitor customer behavior and usage patterns to identify early signs of churn.
Foster customer loyalty and engagement through various channels.
Regularly evaluate and refine the churn prediction model for improved accuracy.
Foster collaboration between departments to ensure a holistic approach to customer retention![image](https://github.com/CliffShitote/dsc.-phase-3-project/assets/124627374/b52412c9-e54a-4c46-bff5-c826490081ca)