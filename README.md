# Fifa-21-Prediction-with-ML-and-Analysis
## Summary of the process:
* Importing the necessary libraries and loading the dataset.
* Performed some basic exploratory data analysis to gain insights into the dataset, including visualizing the distribution of players ages, overall ratings, age vs overall ratings, top 10 nationalities by number of players, checked for top teams, Replace single quote and double quote characters with empty strings, Remove non-numeric characters from weight column and distribution of player positions.
* Preprocessed the dataset by dropping a few columns like 'photoUrl', 'playerUrl', 'Release Clause, I also checked for missing values. created a label encoder object to transform 'foot' from a categorical variable to a numerical value and detected outliers.
* Split the data into training and testing sets and used scikit-learn's Logistic Regression to predict the top players.
* Trained a LogisticRegressor on the training set and evaluated its performance on the testing set using metrics such as accuracy, precision, recall, and F1 score.
* Made prediction on the test set, computed and print the confusion matrix and classification report
