# Titanic-Logistic-Regression-Model

This project involves creating a logistic regression model to predict the survival of passengers on the Titanic based on various features such as age, gender, class, and more.

## Dataset

The dataset used for this project is the Titanic dataset was collected from Kaggle and contains information about the passengers who were on board the Titanic. The dataset includes the following columns:

- `PassengerId`: Unique ID for each passenger
- `Survived`: Survival indicator (0 = No, 1 = Yes)
- `Pclass`: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`: Name of the passenger
- `Sex`: Gender of the passenger
- `Age`: Age of the passenger
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Ticket fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Data Preprocessing

The data preprocessing steps include:

1. Importing necessary libraries and reading the dataset.
2. Analyzing the data to understand its structure and identify missing values.
3. Handling missing values by either filling them with appropriate values or dropping them.
4. Dropping unnecessary columns that do not contribute to the model.
5. Encoding categorical variables into numerical values.

## Model Building

The logistic regression model is built using the `scikit-learn` library in Python. The following steps are involved in building the model:

1. Splitting the data into training and testing sets.
2. Training the logistic regression model on the training set.
3. Evaluating the model's performance on the testing set using accuracy, precision, recall, and other metrics.

## Visualization

Various visualizations are created to analyze the data and model performance, including:

- Histograms to show the distribution of numerical features.
- Count plots to show the count of categorical features.
- Heatmaps to show the correlation between different features.

## Conclusion

The logistic regression model provides a good baseline for predicting the survival of Titanic passengers. Further improvements can be made by exploring other machine learning algorithms and feature engineering techniques.

Feel free to explore the notebook and suggest modifications as needed.
