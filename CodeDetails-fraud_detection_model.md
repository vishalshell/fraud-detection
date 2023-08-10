## Code Analysis
The given code is a Python script for building and evaluating fraud detection models using machine learning algorithms.
It uses libraries such as pandas, scikit-learn, and imbalanced-learn for data manipulation, model training, and evaluation.

Here's a breakdown of what the code does:

## Data Loading and Preprocessing:
Loads a CSV file named fraud_detection1.csv using pandas.
Separates the dataset into features (input variables) and labels (target variable).
Encodes non-numeric categorical columns using LabelEncoder.
Converts the string value "PAYMENT" to the float value 0 in categorical columns.

## Data Splitting and Resampling:
Splits the data into training and test sets using train_test_split.
Applies Synthetic Minority Over-sampling Technique (SMOTE) to balance the class distribution by oversampling the fraud transactions.

## Model Creation and Training:

Creates three different machine learning models: Logistic Regression, Decision Tree, and Random Forest.
Trains each of the models on the training data.

## Model Evaluation:
Evaluates the trained models on the test set.
Calculates metrics such as Accuracy, Precision, Recall, and F1-score for each model.

## Results Presentation:
Stores the evaluation results in a dictionary and creates a Pandas DataFrame from the dictionary.
Displays the evaluation results in tabular format using the DataFrame.
Plots a graph to visualize the Accuracy of each model using matplotlib.
