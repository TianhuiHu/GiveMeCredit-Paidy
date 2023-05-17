# GiveMeCredit-Paidy
Improve on the state of the art in credit scoring by predicting the probability that somebody will experience financial distress in the next two years.
Banks play a crucial role in market economies. They decide who can get finance and on what terms and can make or break investment decisions.

For markets and society to function, individuals and companies need access to credit. Credit scoring algorithms, which make a guess at the probability of default, are the method banks use to determine whether or not a loan should be granted. This competition requires participants to improve on the state of the art in credit scoring, by predicting the probability that somebody will experience financial distress in the next two years. The goal of this competition is to build a model that borrowers can use to help make the best financial decisions.

==>The goal of this project is to build a model that borrowers can use to help make the best financial decisions. (PD model)

Historical data are provided on 150,000 borrowers.https://www.kaggle.com/c/GiveMeSomeCredit

## Usage

Provide instructions and examples for how to use your project. This can include code snippets, command-line instructions, or screenshots.

preprocess.py Running this script will preprocess training dataset and saves essential items to ensure that the test dataset goes through the same preprocessing steps. Output items will be a pickled dictionary containing values for imputation (if activated), and preprocessed dataset in the data/ folder.

train.py Running this script will train a classic machine learning model on the preprocessed training dataset and saves the model. The model file can be found in model_output/ folder.

generate_predictions.py Running this script will allow the trained model to generate predictions for the test dataset. The predictions can be found in a csv contained within model_output/ folder.

## Contributing

Explain how others can contribute to your project. Provide guidelines for submitting pull requests, reporting issues, or suggesting improvements.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact
- Email: crystalhu0106@gmail.com.com


Best Parameters for XGBoost
subsample: 0.6
reg_lambda: 0
reg_alpha: 0
n_estimators: 550
min_child_weight: 6
max_depth: 8
learning_rate: 0.007
gamma: 0.4
colsample_bytree: 0.6
booster: gbtree
random_state: 0
