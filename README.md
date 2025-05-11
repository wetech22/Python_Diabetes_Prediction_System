# Python_Diabetes_Prediction_System
# Diabetes Prediction with SVM
This notebook uses machine learning to predict whether someone is diabetic based on a bunch of health parameters like glucose level, BMI, insulin, and even number of pregnancies. 

# Tools and Libraries Used
Pandas and NumPy – for handling and analyzing data  
Scikit-learn – for:  
--Standardizing the data using StandardScaler  
--Splitting the dataset into training and test sets  
--Applying Support Vector Machine (SVM) with a linear kernel  
--Calculating accuracy to evaluate model performance  
--Dataset: diabetes.csv (Pima Indians Diabetes Dataset)

# Workflow
Data Exploration – Looked at dataset shape, value counts, means, and grouped stats by Outcome.  
Feature Standardization – Because the values had serious mood swings.  
Model Training – Used SVM to train on 80% of data.  
Prediction – Model takes 8 health values as input and predicts diabetic status.  
Result Interpretation – Binary output (0 or 1) tells whether the person is diabetic or not.

# Accuracy
Training Accuracy: Around 78.66%  
Decent accuracy for a basic linear model with minimal tuning

# Sample Input
[5, 166, 72, 19, 175, 25.8, 0.587, 51]  
Prediction: Diabetic. So yes, this model can detect patterns better than that one friend who always thinks you’re sick if you skip chai once.

# Files Included
diabetes_prediction.ipynb – The main notebook with all steps  
diabetes.csv – The dataset used  
README.md – This file, explaining what’s going on and why

# Why This Project?
Because predicting diseases early can make a real difference. Also, building machine learning projects that actually mean something is far more satisfying than just chasing accuracy scores. This one’s practical, simple, and fun to build.

# Disclaimer
This project is meant for educational purposes only. Not to be used for actual medical diagnosis. Always consult a professional.
