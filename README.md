## Breast Cancer Classification

This notebook demonstrates a simple breast cancer classification using Logistic Regression on the Wisconsin Diagnostic Breast Cancer (WDBC) dataset.

## Steps:

1.  **Import Dependencies**: Import necessary libraries such as `numpy`, `pandas`, and modules from `sklearn`.
2.  **Data Collection and Preprocessing**:
    *   Load the breast cancer dataset from `sklearn.datasets`.
    *   Convert the dataset to a pandas DataFrame.
    *   Add the target variable ('label') to the DataFrame.
    *   Perform basic data exploration (check head, tail, shape, info, missing values, describe, and value counts).
3.  **Separate Features and Target**: Divide the DataFrame into features (X) and the target variable (Y).
4.  **Split Data**: Split the data into training and testing sets using `train_test_split`.
5.  **Model Training**:
    *   Initialize a Logistic Regression model.
    *   Train the model using the training data.
6.  **Model Evaluation**:
    *   Calculate and print the accuracy score on both training and testing data.
    *   Generate and print the confusion matrix for the test data.
    *   Calculate and print precision and recall scores.
    *   Calculate and print the ROC-AUC score.
    *   Explain the sigmoid function.
    *   Tune the prediction threshold and visualize its effect on accuracy.
7.  **Summary**: Provide a summary of the data analysis key findings and insights.
