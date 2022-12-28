# Online-Payment-Fraud-Detection
10Alytics Capstone Project- Online Payment Fraud Detection Machine Learning
Problem Definition
This Project aims to solve the challenge of accurately and precisely identifying fraudulent online payment transactions. This is a significant issue for Blossom Bank that process online payments, as fraud can result in financial losses and damage to its reputation.

How will the business benefit from this project?
By using machine learning to develop a predictive model for identifying fraudulent transactions, Blossom Bank Plc can potentially reduce their losses from online payment fraud. This can be achieved by automatically flagging potentially fraudulent transactions in real-time, allowing the bank to take appropriate action to prevent or minimize losses. Additionally, by using machine learning to identify the factors that are most indicative of online payment fraud, Blossom Bank Plc can better understand the patterns and tactics used by fraudsters, and take steps to prevent future incidents.

Overall, the solution provided by the Online Payment Fraud Detection Machine Learning Project can help Blossom Bank Plc to reduce their exposure to online payment fraud, and protect their financial and reputational interests.

Dataset is available here https://drive.google.com/file/d/1ZIjmAjPccvy16mOk7nrPtWe-_3rRP5zy/view?usp=sharing

I performed some exploratory data analysis (EDA) on the dataset. The EDA is meant to gain insights into the data and identify any patterns or trends that may be useful in developing a machine learning model to detect fraudulent transactions.

I imported several libraries including pandas, numpy, matplotlib, and seaborn. I then loaded the data into a Pandas DataFrame and used various functions such as describe(), info(), value_counts(), groupby(), and map() to explore the data and understand the characteristics of the variables in the dataset.

Several visualization techniques such as bar plots and count plots to visualize the data and identify any trends or patterns were deployed. For example, I plotted the total payments by online transaction type and the type of online transactions to understand which types of transactions are most common and which are most likely to be fraudulent.

Overall, the EDA appears to be aimed at understanding the characteristics of the dataset and identifying any factors that may be useful in developing a machine learning model to detect fraudulent transactions.

The data was preprocessed into a format suitable for modeling. This included encoding of categorical variables, dividing the dataset into training and testing sets as well as addressing the imbalanced class in the target column.

Two supervised machine learning models, Random Forest & K-nearest Neighbors was trained using the training dataset and were tested on the test dataset.

The classification report and confusion matrix were used to evaluate the models. Since the goal of my model is to maximize the sensitivity of the model to detecting fraudulent transactions, I was particular about the F1 score.
