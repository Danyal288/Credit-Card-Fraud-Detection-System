# Credit-Card-Fraud-Detection-System using Random forest model
# Description

This project focuses on developing a fraud detection system using a dataset from Kaggle, Credit Card Fraud Dataset. The system is designed to classify transactions as fraudulent or legitimate using machine learning techniques. 
# EXPLORATORY DATA ANALYSIS
** Data Preprocessing**
Proper preprocessing ensures data quality and suitability for machine learning models: perfromed EDA process.
In this project I used the concept of undersampling to balance my dataset. Since fraud cases are rare. i removed any duplicates and joined the balanced Dataset using concat function.


# Model
**Model Traning**
for traning model first I have to split the dataset using train_test_split function.
Then I used the RandomForest Model to train on dataset. I use .fit()fuction to train it.
*Random Forest Classifier: An ensemble method that combines multiple decision trees.*

on Traninf data theAccuracy score was :  0.9936467598475223 or 99%

**Model Testing**
After traning model on traning dataset I then test the MODEL on teat dataset and for that I used .predict() function

Accuracy score on test data :  0.9187817258883249 or 91%

# Model Evaluation
For Evalution perpose I used Confusion Matrix: Visual representation of true positives, false positives, true negatives, and false negatives.


# Result

The model was sucessfully built and gave a good score on test data around 91%.
