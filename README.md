**Project Overview**
This project is dedicated to optimizing response strategies for the New York Police Department (NYPD) through advanced data-driven insights and efficient resource allocation. The goal is to classify historical shooting incidents as fatal or non-fatal, thereby enhancing the prioritization and effectiveness of response efforts.

**Dataset Details**
1. Objective: Classify shooting incidents into fatal or non-fatal categories.
2. Dataset Dimensions: 27,312 records with 21 features.

**Data Preprocessing**
1. Column Removal: Excluded non-essential columns such as 'OCCUR_DATE', 'OCCUR_TIME', 'BORO', 'LOC_OF_OCCUR_DESC', 'LOC_CLASSFCTN_DESC', 'LOCATION_DESC', 'PERP_AGE_GROUP', 'PERP_SEX', 'PERP_RACE', 'VIC_AGE_GROUP', 'VIC_SEX', 'VIC_RACE', and 'Lon_Lat'.
2. Encoding: Implemented label encoding to convert categorical variables into numerical format.
3. Outlier Detection: Applied Isolation Forest for outlier detection and removal to ensure data quality.
4. Class Imbalance: Addressed class imbalance using the Synthetic Minority Over-sampling Technique (SMOTE) to enhance the representation of minority classes.

**Model Evaluation**
Seven machine learning algorithms were assessed to determine the optimal model for predicting shooting incident severity:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting
5. Support Vector Machine
6. Naive Bayes
7. K-Nearest Neighbors
Results: The Random Forest Classifier demonstrated superior performance, achieving an accuracy of 74.50%.

**Conclusion**
The Random Forest Classifier emerged as the most effective model for predicting shooting incident outcomes. This achievement is a result of rigorous data preprocessing, including the management of categorical features, handling missing values, and mitigating class imbalance.

