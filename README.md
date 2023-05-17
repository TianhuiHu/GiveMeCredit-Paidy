# GiveMeCredit-Paidy
Improve on the state of the art in credit scoring by predicting the probability that somebody will experience financial distress in the next two years.
Banks play a crucial role in market economies. They decide who can get finance and on what terms and can make or break investment decisions.

For markets and society to function, individuals and companies need access to credit. Credit scoring algorithms, which make a guess at the probability of default, are the method banks use to determine whether or not a loan should be granted. This competition requires participants to improve on the state of the art in credit scoring, by predicting the probability that somebody will experience financial distress in the next two years. The goal of this competition is to build a model that borrowers can use to help make the best financial decisions.

==>The goal of this project is to build a model that borrowers can use to help make the best financial decisions. (PD model)

Historical data are provided on 150,000 borrowers.https://www.kaggle.com/c/GiveMeSomeCredit

## Scripts

EDA.ipnyb in this notebook, an exploratory data analysis is performed on Give Me Some Credit's training set and preprocessing advice will be given accordingly.

preprocessing.ipynb Running this script will preprocess training dataset and saves essential items to ensure that the test dataset goes through the same preprocessing steps. Output items  and preprocessed dataset in the csv/ folder. 

model_selection.ipynb Running this script will train a classic machine learning model on the preprocessed training dataset and saves the model. The model file can be found in models/ folder.

Model_Tunning.ipynb Running this script will allow the trained model to generate predictions for the test dataset. The predictions can be found in a csv contained within model_output/ folder.

Model Validation.ipynb Running this script will provide final step - model validation

## License

This project is licensed under the [MIT License](LICENSE).

## Contact
- Email: crystalhu0106@gmail.com.com


## Best Parameters for XGBoost
xgb__colsample_bytree: 0.9
xgb__eta:0.1
xgb__max_depth:3
xgb__n_estimators:100

## Best Parameters for RandomForest
criterion: 'entropy',
max_depth: 'None', 
n_estimators: 200
