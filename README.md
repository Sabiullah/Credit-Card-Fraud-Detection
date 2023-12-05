# Credit-Card-Fraud-Detection

**Introduction**
The project aimed to predict credit card fraud using machine learning techniques. The dataset, sourced from Kaggle, consisted of credit card transactions, highly imbalanced, with 492 frauds among 284,807 transactions. The report explores feature selection, modeling using various classifiers, and evaluates model performance under different sampling techniques.

**Table of Contents**

1.	Technologies Used
2.	Data Overview
Description of the Dataset
Exploratory Data Analysis (EDA)
3.	Feature Selection
  Top Variables for Prediction
  PCA Implementation
4.	Modeling
  Logistic Regression
  Decision Tree Classifier
  Support Vector Machines (SVM)
5.	Conclusion
  Summary of Findings
  Model Comparison and Recommendations


**Key Technologies and Skills**
- Python
- Pandas
- Logistic Regression
- Decision Tree Classifier
- Support Vector Machines (SVM)
- seaborn
- matplotlib



**Data Overview**

- Exploratory Data Analysis (EDA)
The data set contains 284807 rows and 31 columns, and found 1081 duplicated rows, after removing all the duplicated rows found the actual data that 473 fraud transactions and 283253 normal transactions.


**Feature Selection:**
- Top Variables for Prediction
Explanation of the most influential variables for predicting fraud, potentially derived from correlation analysis or feature importance.
- PCA Implementation
By doing correlation matrix heatmap found top top features of the class and keep the high featured columns alone with Class and removed rest of the columns from the data set to proceed further modelling.

**Modeling:**
- Under Sampling
- Over Sampling

**Conclusion**
***Under Sampling***
Logistic Regression: High accuracy and decent across other metrics.
Decision Tree Classifier: Good overall performance but slightly lower precision and F1 score compared to the other models.
SVM Method: High accuracy and balanced precision, recall, and F1 score.

***Oversampling***
Logistic Regression: Slightly improved performance across all metrics.
Decision Tree Classifier: Significant improvement in all metrics, almost perfect scores.
SVM Method: Improved accuracy and precision, slightly lower recall but an improved F1 score.

***Model Selection:***
Based on the provided results, the oversampling method has notably improved the performance of all models. The Decision Tree Classifier, in particular, exhibits impressive performance with almost perfect scores across the board in the oversampling scenario.



  **Contact**

📧 Email: safycosting@gmail.com

🌐 LinkedIn: https://www.linkedin.com/posts/sabiullah-noor-mohamed-83507386

For any further questions or inquiries, feel free to reach out. We are happy to assist you with any queries.
