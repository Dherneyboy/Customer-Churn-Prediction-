# Customer Churn Prediction using Artificial Neural Networks (ANN)

## Overview
This project focuses on predicting customer churn using an Artificial Neural Network (ANN). We will analyze the Telco-Customer-Churn dataset from Kaggle. The dataset contains information about Telco customers and whether they churned or not.
What is Customer Churn?
Customer churn is when customers stop using a service or product. In our case, it means customers leaving the Telco service.
## Business Understanding
Predicting customer churn in the telecom industry has significant business implications:

1.	Reducing Customer Attrition:
   
•	Identifying potential churners allows telecom companies to take proactive measures to retain customers.

•	By addressing issues early (e.g., personalized offers, improved service), companies can reduce attrition rates.

2.	Cost Savings:

•	Acquiring new customers is more expensive than retaining existing ones.

•	Predictive models help allocate resources efficiently by focusing on high-risk customers.

3.	Improving Customer Experience:

•	Churn prediction enables targeted communication with at-risk customers.

•	Companies can address pain points, enhance service quality, and increase customer satisfaction.

4.	Revenue Growth:

•	Retaining loyal customers leads to longer customer lifetimes and increased revenue.

•	Churn prediction contributes to overall business stability and growth.
In summary, churn prediction empowers telecom companies to optimize operations, enhance customer relationships, and drive business success.


## Data Understanding

#### Data Source: Kaggle; Dataset: Telco-Customer-Churn.csv 

#### Link to dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

### Data Description

The dataset contains  7043 rows with 21 columns. Each row represents a customer, each column contains the customer’s attributes described in the column Metadata.
The data set includes information about:

•	Customers who left within the last month – the column is called Churn

•	Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies

•	Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges

•	Demographic info about customers – gender, age range, and if they have partners and dependents.

## Tools Used

Programming Language: Python

Libraries: Pandas, Numpy, Matplotlib, Sklearn, seaborn, TensorFlow, and Keras.

Processes: Exploratory Data Analysis (EDA), Data Visualization, one hot encoding, Scaling, Machine Learning, Artificial Neural Network (ANN)

## Model Evaluation and Result

An Artificial Neural network(ANN) was used to predict whether a customer will churn or not. The data below shows the classification report from the model.

 ![image](https://github.com/Dherneyboy/Customer-Churn-Prediction-/assets/148950017/25bc4544-0e79-44b6-8b55-b040174f4f4d)

## Insight

•	customers with longer tenure seem to be more loyal(i.e. will not churn) compared to new customers

![image](https://github.com/Dherneyboy/Customer-Churn-Prediction-/assets/148950017/a0c29114-0391-48b7-a363-90d991cc8fc7)

 
•	As the monthly charges increase the number of customers that churn increases.

![image](https://github.com/Dherneyboy/Customer-Churn-Prediction-/assets/148950017/411179a7-b2e8-4405-8fa9-55a1066f21da)

 
## Conclusion

In this study, we employed an Artificial Neural Network (ANN) to predict customer churn in the Telecom industry. With an accuracy of approximately 80%, our model demonstrates promising performance. However, further investigation into feature importance and potential business implications is recommended.
