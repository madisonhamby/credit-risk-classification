
# Credit Risk Analysis Report 
1. Explain the purpose of this analysis
- The objective of this analysis is to develop and assess the effectiveness of a data model aimed at predicting the creditworthiness of prospective borrowers within peer-to-peer lending platforms.

2. Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model.
- Balanced Accuracy Score: 95.2% 
    - This score is the average between the sensitivity (recall/true positive rate) and the specificity (true negative rate). An accuracy score of 95.2% indicates a near perfect classifier. 
- Precision Score: 92% 
    - This score asserts that 92% of predicted positives were correct. 
- Recall Score: 95%
    - This score indicates that the model achieved a precision rate of 95% in accurately identifying true positive values among all positive predictions generated.


3. Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. 

- I suggest utilizing this model for predicting borrower creditworthiness due to its accuracy of over 95% in forecasting the repayment outcome of the initial loan. This level of accuracy can be effectively incorporated into a business risk profile, ensuring adequate capital flow for lenders to sustain operations and generate profits.

# Instructions 
Background
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The instructions for this Challenge are divided into the following subsections:

- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Write a Credit Risk Analysis Report

## Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

3. Split the data into training and testing datasets by using train_test_split.

## Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

1. Fit a logistic regression model by using the training data (X_train and y_train).

2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

3. Evaluate the model’s performance by doing the following:
- Generate a confusion matrix.
- Print the classification report.

4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

1. An overview of the analysis: Explain the purpose of this analysis.

2. The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

3. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.