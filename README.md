# Classification-on-heart-disease

This project focuses on predicting the presence of heart disease in patients using three different machine learning algorithms: Support Vector Classifier (SVC), Random Forest, and Logistic Regression. The primary goal is to develop a robust model that can accurately classify patients based on their medical attributes.

## Methodology

## 1. Data Preprocessing

The dataset is first cleaned and preprocessed to handle missing values, normalize numerical features, and encode categorical variables. This step ensures that the data is in a suitable format for training machine learning models.

## 2. Exploratory Data Analysis (EDA)

EDA is performed to understand the distribution of features, identify correlations, and visualize relationships between features and the target variable. This step helps in feature selection and engineering.

## 3. Model Training

Three machine learning algorithms are used for classification:

## Support Vector Classifier (SVC):

A powerful classification algorithm that works well on high-dimensional data.
## Random Forest: 

An ensemble learning method that constructs multiple decision trees and merges them to get a more accurate and stable prediction.
## Logistic Regression:

A statistical model that in its basic form uses a logistic function to model a binary dependent variable.


Each model is trained on the preprocessed dataset, and hyperparameter tuning is performed using techniques like GridSearchCV to find the best parameters.

## 4. Model Evaluation

The models are evaluated based on various metrics such as accuracy, precision, recall, F1-score, and ROC-AUC score. Cross-validation is used to ensure the robustness of the models. The results are compared to determine the best-performing model.

## 5. Model Deployment

The final model is saved and can be used for predicting heart disease on new patient data. An API or a web application can be built around this model for real-time predictions.

## Results

The performance of each model is compared, and the results are documented in terms of accuracy, precision, recall, F1-score, and ROC-AUC score. Visualizations such as confusion matrices and ROC curves are included to illustrate the model performance.

## Conclusion

This project demonstrates the application of machine learning techniques to predict heart disease. By comparing different models, we can select the most effective one for this classification task, contributing to better healthcare decisions and potentially saving lives.
