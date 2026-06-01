<h1>Customer Churn Prediction (Logistic Regression Pipeline)</h1> <h2>Description</h2>

This project is a machine learning model that predicts customer churn using structured data. It uses a Scikit-learn pipeline to handle preprocessing, train a Logistic Regression model, and evaluate performance.

The model automatically encodes categorical variables, keeps numerical features unchanged, and outputs both predictions and probability scores.

It is evaluated using accuracy, ROC-AUC, and a full classification report.

<br /> <h2>Core Features</h2>
Splits data into training and testing sets (80/20)
Encodes categorical variables using OneHotEncoder
Builds a Scikit-learn Pipeline for preprocessing and modeling
Uses Logistic Regression for classification
Outputs predictions and probability scores
Evaluates performance using accuracy, ROC-AUC, precision, recall, and F1-score
<br /> <h2>Languages and Utilities Used</h2>
Python
Scikit-learn
Pandas
NumPy
<br /> <h2>System Workflow</h2>
Load dataset (new_df)
Define features and target (Churn)
Identify categorical columns
Encode categorical data
Build ML pipeline
Split data into train and test sets
Train model
Make predictions
Evaluate results
<br /> <h2>Model Evaluation</h2>
Accuracy shows overall performance
ROC-AUC measures how well the model separates classes
Precision, recall, and F1-score show class-level performance
<br /> <h2>File Access</h2>
Run the Python script or notebook to train and test the model
Make sure new_df is loaded before running
<br /> <h2>Preview Note</h2>

If there are issues previewing this file, paste the url of this page into https://nbviewer.org/
