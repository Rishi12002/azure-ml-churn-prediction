Telco Customer Churn Prediction using Azure Machine Learning (No-Code)

This project uses Microsoft Azure Machine Learning Designer (no-code pipeline) to build a Churn Prediction Model using the Telco Customer Churn dataset.
The goal is to identify customers who are likely to leave the telecom service.

Project Highlights

Built using Azure ML Designer (drag-and-drop ML pipeline)

No coding required for training

Used Data Cleaning, Column Selection, Train-Test Split, and Logistic Regression

Registered the model in Azure ML

Model can be deployed as an endpoint (optional)

Clean and beginner-friendly implementation

Azure ML Pipeline Overview

Your pipeline includes:

Dataset (Telco Churn CSV)

Select Columns

Clean Missing Data

Split Data (80/20)

Two-Class Logistic Regression

Train Model

Score Model

Evaluate Model

- Full ML workflow built with Designer (drag & drop)
- No Python code required for training

 Steps Performed
-  Imported the dataset

Uploaded Telco Churn CSV to Azure ML

- Created the ML Pipeline

Added components:

Select Columns

Clean Missing Data

Split Data

Logistic Regression

Train Model

Score Model

Evaluate Model

- Ran the Pipeline

Model was trained successfully

Evaluation metrics were generated

-  Registered the Model

Model name: telco_churn_model

- (Optional) Deployment

Deployment requires:

 -score.py

Environment selection
(But this step is optional for this project)

- Model Performance 
Metric	    Value
Accuracy	  0.813
AUC	       0.85
Precision	 0.636
Recall   	 0.561
F1 Score   0.596
