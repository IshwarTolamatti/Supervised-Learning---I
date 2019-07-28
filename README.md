# Supervised-Learning---I

CaseStudy-1

Questions:
1. We will use acoustic features to distinguish a male voice from female. Load the dataset from “voice.csv”, identify the target variable and do a one-hot encoding for the same. Split the dataset in train-test with 20% of the data kept aside for testing.
[Hint: Refer to LabelEncoder documentation in scikit-learn]

2. Fit a logistic regression model and measure the accuracy on the test set.
[Hint: Refer to Linear Models section in scikit-learn]

3. Compute the correlation matrix that describes the dependence between all predictors and identify the predictors that are highly correlated. Plot the correlation matrix using seaborn heatmap.
[Hint: Explore dataframe methods to identify appropriate method]

4. Based on correlation remove those predictors that are correlated and fit a logistic regression model again and compare the accuracy with that of previous model.
[Hint: Identify correlated variable pairs and remove one among them]

CaseStudy-2

Questions:
1. Let’s attempt to predict the survival of a horse based on various observed medical conditions. Load the data from ‘horses.csv’ and observe whether it contains missing values.
[Hint: Pandas dataframe has a method isnull]

2. This dataset contains many categorical features, replace them with label encoding.
[Hint: Refer to get_dummies methods in pandas dataframe or Label encoder in scikit-learn]

3. Replace the missing values by the most frequent value in each column.
[Hint: Refer to Imputer class in Scikit learn preprocessing module]

4. Fit a decision tree classifier and observe the accuracy.
5. Fit a random forest classifier and observe the accuracy.
