# **Loan Approval Prediction**

This project aims to predict loan approval status using machine learning techniques. The predictive model is built on a dataset containing various attributes related to loan applicants, such as income, credit history, and employment status.

## **Introduction**

The ability to accurately predict loan approval status is crucial for financial institutions to assess the risk associated with lending money. By leveraging machine learning algorithms, this project seeks to automate the loan approval process and improve decision-making efficiency.

## **Overview**

The Loan Approval Prediction project utilizes machine learning techniques to forecast the approval status of loan applications. In today's financial landscape, efficient and accurate loan approval processes are paramount for both financial institutions and applicants. By automating this process through predictive modeling, this project aims to streamline decision-making and enhance risk assessment.

At its core, the project revolves around a dataset comprising diverse attributes related to loan applicants, including but not limited to income levels, credit histories, and employment statuses. Leveraging supervised learning methods, particularly the Naive Bayes algorithm, the project proceeds through several key stages to build and evaluate the predictive model.

## **Libraries**

1. NumPy
2. Pandas
3. scikit-learn (sklearn)

## **Key Features**

1. Data Setup:
Importing datasets and essential libraries.

2. Data Cleaning:
Preprocessing the data to handle missing values and outliers.

3. Encoding Data:
Converting categorical variables into numerical format using label encoding.

4. Data Partitioning:
Splitting the dataset into input and output features.

5. Train-Test Split:
Dividing the data into training and testing sets for model evaluation.

6. Normalizing Data:
Applying StandardScaler normalization to ensure uniformity in feature scaling.

7. Model Creation:
Implementing a Naive Bayes (BernoulliNB) classification model.

8. Performance Evaluation:
Assessing model performance using confusion matrix, accuracy score, and classification reports (recall, precision, f1_score).

9. Graphical Representation:
Visualizing the confusion matrix using Confusion Matrix Display for better insights.

## **Insights**

The developed model achieves an accuracy score of 76%, indicating its potential for predicting loan approval status. Further optimization and feature engineering could potentially enhance model performance.
