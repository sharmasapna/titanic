This repository contains the python code used for predicting the survivors.   



**titanic_EDA_18june2021.ipynb**.  
Highlights:   
This notebook contains EDA   
**titanic_prediction_score_79.186_28july2021.ipynb**
**Improvement in score to 0.79186**   
Highlights:
1. Family feature created by summing Parch, SibSp
2. Isalone,Small_family,Large_family features created where Family 
3. Title feature created from Name by extracting the titles from them and then grouping them
5. Missing value of Embarked filled with mode value
6. Missing value of Age filled with random numbers generated as per mean and standard deviation
7. Cabin and Ticket features were used
8. Feature Importance was used and only 12 features were used for training.
9. RandomForestClassifier gave the best results.
Future Efforts:
1. Stacking the results of different models
2. Missing value of Age imputation method to be changed
3. Hypertunig RandomForestClassifier
4. Try different classifiers



**titanic_prediction_with_score_0.78708_21july2021.ipynb**   
**This is my best Titanic prediction with score of 78.708% till now!**   
Highlights:
1. Family feature created by summing Parch, SibSp
2. Isalone feature created where Family = 0
3. Title feature created from Name by extracting the titles from them and then grouping them
5. Missing value of Embarked filled with mode value
6. Missing value of Age filled with random numbers generated as per mean and standard deviation
7. Bins created for age and farehyoer
8. Columns dropped: Cabin, Ticket,Age,Name,Fare
9. Used Random Forest, Logistic Regression and XGBoost for prediction

Future efforts:
1. Changing the missing value imputation for Age 
2. Keeping the cabin and ticket features
3. Feature selection
4. Stacking results from different models



