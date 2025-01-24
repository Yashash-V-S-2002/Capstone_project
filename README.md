# **Capstone_project**
# **FINDDEFAULT (Prediction of Credit Card Fraud)**
**Problem Statement:**

A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. 
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
We have to build a classification model to predict whether a transaction is fraudulent or not.

**Dataset Description:**

It contains only **numerical input variables** which are the result of a **PCA transformation**. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features **V1, V2, … V28** are the principal components obtained with PCA. The only features which have not been transformed with PCA are **'Time' and 'Amount'**.

Feature **'Time'** contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature **'Amount'** is the transaction amount, and this feature can be used for example-dependant cost-sensitive learning. Feature **'Class'** is the response variable, and it takes the value **1** in case of fraud and **0** otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the **Area Under the Precision-Recall Curve (AUPRC)**. Confusion matrix accuracy is not meaningful for unbalanced classification.

**Machine Learning Model:**

Models used in this notebook:

    1.  Logistic Regression

    2.  Random Forest

    3.  Extra Tree Classifier

    4.  AdaBoost

    5.  Gradient Boosting

    6.  LightGBM

**Objectives:**

This notebook **aims** to:

    1.  **Analyze** the dataset using various visualization techniques to uncover patterns and insights.

    2.  **Develop** a predictive machine learning model for classifying fraudulent transactions

    3.  **Identify and analyze** the signs that can be used to determine whether an operation is fraudulent.

**Conclusion and Next Steps:**

This section summarizes the **key findings** and highlights the **insights** gained from the analysis. It also outlines possible next steps to further improve the model or extend the study.

This project successfully analyzed a highly imbalanced dataset of credit card transactions to identify fraudulent activities. Key insights include:

    1.  Explored **PCA-transformed** features for data understanding and visualization.
    2.  Developed machine learning models including **Logistic Regression, Random Forest**, and advanced gradient boosting techniques **(LightGBM).**
    3.  Evaluated models using **AUPRC** to handle class imbalance effectively.
    
The models demonstrated strong performance, especially when handling imbalanced classes, by leveraging advanced sampling and evaluation techniques.

**Next Steps:**

To further enhance the project, the following steps are recommended:

    1.Experiment with ensemble techniques such as **Stacking** and **Blending** to combine model predictions.
    2.Incorporate additional data sources or engineered features to improve model performance.
    3.Deploy the model in a real-world environment and monitor its performance over time.
    4.Explore techniques for real-time fraud detection using streaming data.

By implementing these steps, the project can be further optimized for scalability and deployment in production systems
