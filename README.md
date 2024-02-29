Childhood Obesity Prediction
Overview
This repository contains the code used for the analysis and prediction of childhood obesity based on socioeconomic factors, utilizing machine learning techniques. The project aims to explore whether factors such as family situation, child behavior, activity level, and lifestyle can effectively predict obesity in children aged 10-17. The code provided here includes data preprocessing, model training, evaluation, and visualization.

Data
The data used for this project is sourced from the National Survey of Children’s Health, providing rich information on children’s wellness, including physical and mental health, access to healthcare, and social context. The dataset consists of 20,091 entries and 864 features. After cleaning, preprocessing, and feature selection, the final dataset contains 67 relevant parameters.

Methods and Approaches
The primary approach involves the following steps:

Data Cleaning: Irrelevant features were removed, and data for children aged 0-9 were excluded due to insufficient BMI information.
Data Preprocessing: The cleaned data was stratified and split into training and test sets. Standard scaling and imputation were applied, and unnecessary columns were dropped.
Model Selection and Training: Various classification algorithms were trained and compared, including Support Vector Classifier (SVC), decision tree, XGBoost, logistic classifier, and basic neural network. Grid search with k-fold cross-validation was used to tune hyperparameters.
Evaluation: Classification reports, confusion matrices, and ROC curves were generated to assess the performance of each model.
