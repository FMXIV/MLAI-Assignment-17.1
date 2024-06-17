Bank Marketing Campaign Analysis

This project aims to predict whether a client will subscribe to a term deposit based on a set of features derived from a marketing campaign conducted by a Portuguese banking institution. We applied the CRISP-DM methodology to guide our analysis and modeling. Here’s a summary of our findings:

Business Understanding
The business objective is to improve the marketing campaigns of the bank by predicting the likelihood of a client subscribing to a term deposit. By accurately identifying potential customers, the bank can target its marketing efforts more effectively, thereby increasing the success rate of its campaigns.

Data Understanding
The dataset contains information about clients and the results of various marketing campaigns, including both categorical and numerical features. The target variable is binary, indicating whether the client subscribed to a term deposit.

Data Preparation
Missing values were checked and handled.
Categorical variables were converted to numerical values using Label Encoding.
The dataset was split into training and testing sets.
Numerical features were standardized.

Modeling
We evaluated the performance of four classifiers:

K-Nearest Neighbors (KNN)
Logistic Regression
Decision Tree
Support Vector Machine (SVM)


Evaluation
Each model was evaluated based on accuracy, precision, recall, and F1-score. Here are the key findings:

Logistic Regression achieved the highest accuracy (89%) and precision but had low recall for the positive class.
Decision Tree provided a balanced performance with good interpretability.
KNN and SVM had high accuracy but lower recall and F1-scores for the positive class, indicating they missed many positive cases.

Conclusion
Logistic Regression is recommended for its high accuracy and precision.
Decision Trees are useful for understanding the decision-making process and identifying key factors.
SVM and KNN need further tuning to improve their recall and F1-scores