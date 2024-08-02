# Customer_churn

Introduction
This project focuses on building a classification model using the Random Forest algorithm to predict customer churn. The dataset used is the customer churn dataset, which contains information about customers and whether they have churned.

Table of Contents
Introduction About the Dataset Data Preprocessing Exploratory Data Analysis (EDA) Implementing Random Forest Model Performance Evaluation Conclusion

About the Dataset
The customer churn dataset contains information about customers and their usage of telecom services. The key features include:

customerID: Customer ID gender: Gender of the customer SeniorCitizen: Whether the customer is a senior citizen Partner: Whether the customer has a partner Dependents: Whether the customer has dependents tenure: Number of months the customer has stayed with the company PhoneService: Whether the customer has phone service MultipleLines: Whether the customer has multiple lines InternetService: Type of internet service OnlineSecurity: Whether the customer has online security OnlineBackup: Whether the customer has online backup DeviceProtection: Whether the customer has device protection TechSupport: Whether the customer has tech support StreamingTV: Whether the customer has streaming TV StreamingMovies: Whether the customer has streaming movies Contract: Type of contract PaperlessBilling: Whether the customer has paperless billing PaymentMethod: Payment method MonthlyCharges: Monthly charges TotalCharges: Total charges Churn: Whether the customer has churned

Data Preprocessing
Loading Data:
Loaded the dataset into a pandas DataFrame for inspection.

Handling Missing Values:
Identified and handled missing values in the dataset by converting the TotalCharges column to numeric and filling missing values with appropriate statistics.

Encoding Categorical Variables:
Converted categorical variables into numerical format using label encoding. Exploratory Data Analysis (EDA)

Descriptive Statistics:
Reviewed the basic statistics and structure of the dataset.

Null Values Check:
Checked for null values in the dataset and calculated the percentage of missing values.

Implementing Random Forest
Feature and Target Selection:
Selected features (X) and target (Y) for the model.

Data Splitting:
Split the dataset into training and testing sets using an 80-20 split.

Training the Random Forest Model:
Trained a Random Forest classifier using the training data. Predicted the churn status for the test data using the trained model.

Model Performance Evaluation
Confusion Matrix:
Generated a confusion matrix to evaluate the performance of the classification model.

Accuracy Score:
Calculated the accuracy score of the model to measure its performance.

Classification Report:
Generated a classification report to provide precision, recall, and F1-score for the model.

Optimizing Number of Trees:
Evaluated the model's accuracy with different numbers of trees to determine the optimal number.

Conclusion
The analysis demonstrated the application of the Random Forest algorithm for predicting customer churn. Key findings include:

The Random Forest classifier provided a reasonable accuracy for predicting customer churn. The model performance was evaluated using accuracy score, confusion matrix, and classification report. Optimizing the number of trees in the Random Forest improved the model's performance. These insights highlight the utility of the Random Forest algorithm in classification tasks, particularly when dealing with datasets with a mix of categorical and numerical features. This approach can be applied to various scenarios where predicting customer behavior is crucial for business decisions.
