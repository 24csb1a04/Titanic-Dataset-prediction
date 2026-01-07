# Titanic-Dataset-prediction
This project aims at making prediction for titanic dataset available on Kaggle. The above project gave an accuracy of 78.7% on submission in Kaggle. (with username adishriml)

# Stages of the project 
This project comprises of the following stages:  
1. Preprocessing : Removal of irrelevant columns from the initial dataset, transformation of data to extract useful information.
2. Training      : The final data is then split into training-testing (80-20) and trained of Random Forest model.
3. Hyperparameter tuning : The various parameters of Random Forest Classifier are adjusted and their accuracies are plotted. We take the best of hyperparameters.
4. Extraction of best-performing model : After training we train the same classifier over various epochs and consider the best performing model over all the epochs.
5. Prediction : The best-performing model was saved in .pkl file. It is now loaded and used for making prediction on test data after performing the same preprocessing n test data.
