# PRODIGY_DS_03

### Bank Marketing Campaign Success Prediction using Decision Trees

### Overview

This repository contains an exploratory data analysis and machine learning solution aimed at predicting whether a client will subscribe to a term deposit following a targeted telephone marketing campaign conducted by a Portuguese banking institution.

The core goal is to build a classification model that can accurately identify potential subscribers ('yes') to optimize future campaign efficiency and resource allocation.


### Dataset

The project utilizes the bank-additional.csv dataset, which includes 4,119 records collected from a bank's direct marketing efforts.

The dataset features include:

  - Client Data: Age, job, marital status, education, default status, housing loan, personal loan.

  - Campaign Data: Contact type, month, day of week, last contact duration (duration), number of contacts performed during this campaign (campaign), days since the client was last contacted (pdays), number of contacts performed before this campaign (previous), and outcome of the previous marketing campaign (poutcome).

  - Social & Economic Context: Employment variation rate, consumer price index, consumer confidence index, Euribor 3-month rate, and number of employees.



 ### Methodology
 
The analysis and modeling are conducted in the Decision_tree_task3.ipynb Jupyter Notebook.


 ### Key Steps:
 
 * Data Loading and Preprocessing: Initial inspection of the data, handling missing values, and encoding categorical variables (e.g., using one-hot encoding or label encoding).

 Feature Scaling: Preparing numerical features for modeling.

 Model Training: A Decision Tree Classifier is trained on the preprocessed data.

 Evaluation: The model's performance is evaluated using standard classification metrics such as accuracy, precision, recall, and the confusion matrix.

 Visualization: The trained Decision Tree structure is visualized to provide insights into the rules the model uses to make predictions.
