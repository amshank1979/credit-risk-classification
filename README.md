Purpose

The purpose of this analysis is to assess and compare the performance of two machine learning models for the task of loan risk assessment. Specifically, we aim to evaluate the original Logistic Regression model and the same model trained on oversampled data using the RandomOverSampler technique. The goal is to determine which model provides better predictions in terms of accuracy, precision, and recall for both healthy loans (label 0) and high-risk loans (label 1).

The financial information in the provided data is related to lending activities, specifically from a peer-to-peer lending services company. The goal of the analysis is to predict the creditworthiness of borrowers based on the available financial data.    The primary objective of the analysis is to predict the "loan status" of borrowers, which typically falls into two categories: "0" representing healthy loans, where borrowers are expected to make payments on time, and "1" representing high-risk loans, where there might be concerns about timely repayment.
The prediction of loan status is critical for the peer-to-peer lending company to make informed decisions about approving or rejecting loan applications. The company wants to minimize the risk of loan defaults by identifying high-risk borrowers, while also ensuring they provide opportunities to creditworthy individuals.

Methods Used

•	Machine Learning
•	Logistic Regression
•	Confusion Matrix

Language

•	Python

Module

•	skicit-learn
•	matplotlib
•	pandas
•	numpy
•	seaborn

Stages of Machine Learning

1.	Data Collection:

•	Gather the dataset containing relevant information about loans and borrowers.

2.	Data Preprocessing:

•	Clean the data by handling missing s, outliers, and formatting issues.

•	Convert categorical variables into numerical format using techniques like one-hot encoding.

•	Split the data into features (independent variables) and the target variable (loan risk or creditworthiness).

3.	Exploratory Data Analysis (EDA):

•	Analyze and visualize the data to gain insights into the relationships between variables.

•	Identify correlations and patterns in the data that may be relevant to loan risk assessment.

Conclusion
Based on the Classification Report, the highest F1-score was obtained in the decision tree model of 0.92 or 92%, the result of which is close to 1, indicating that the model performance is very good. The interpretation of the results obtained by researchers has the conclusion that to find out whether a debtor is eligible to receive credit or not by taking into account the amount of annual income, loan class, interest rate, percent of income, home ownership mortgage/rent, history of default. In the application that is formed, when it is submitted, it will appear approved or rejected according to the eligibility level of the recipient of the credit customer.
