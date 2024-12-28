# Customer Churn Prediction

This repository contains the code and dataset used for predicting customer churn for a telecommunications company. The goal of this project is to leverage machine learning techniques to identify customers who are likely to leave the service.

## Project Structure

The project consists of the following files and folders:

-   `Customer Churn Prediction.ipynb`: Jupyter Notebook containing the code for data exploration, preprocessing, model building, and evaluation.
-   `WA_Fn-UseC_-Telco-Customer-Churn.csv`: Dataset used for the analysis.

## Dataset Overview

The dataset, `WA_Fn-UseC_-Telco-Customer-Churn.csv`, contains information about telecom customers and whether they have churned (left the company) or not.

### Dataset Features:

The dataset contains the following columns:

-   `customerID`: Unique identifier for each customer.
-   `gender`: Gender of the customer (Male/Female).
-   `SeniorCitizen`: Whether the customer is a senior citizen (1/0).
-   `Partner`: Whether the customer has a partner (Yes/No).
-   `Dependents`: Whether the customer has dependents (Yes/No).
-   `tenure`: Number of months the customer has stayed with the company.
-   `PhoneService`: Whether the customer has phone service (Yes/No).
-   `MultipleLines`: Whether the customer has multiple lines (Yes/No/No phone service).
-   `InternetService`: Type of internet service (DSL/Fiber optic/No).
-   `OnlineSecurity`: Whether the customer has online security (Yes/No/No internet service).
-   `OnlineBackup`: Whether the customer has online backup (Yes/No/No internet service).
-   `DeviceProtection`: Whether the customer has device protection (Yes/No/No internet service).
-   `TechSupport`: Whether the customer has tech support (Yes/No/No internet service).
-   `StreamingTV`: Whether the customer has streaming TV service (Yes/No/No internet service).
-   `StreamingMovies`: Whether the customer has streaming movies service (Yes/No/No internet service).
-   `Contract`: Type of contract (Month-to-month/One year/Two year).
-   `PaperlessBilling`: Whether the customer has paperless billing (Yes/No).
-   `PaymentMethod`: Payment method (Electronic check/Mailed check/Bank transfer (automatic)/Credit card (automatic)).
-   `MonthlyCharges`: Monthly charges for the customer.
-   `TotalCharges`: Total charges for the customer.
-   `Churn`: Target variable indicating whether the customer churned (Yes/No).

## Methodology

### 1. Data Exploration

-   Understand the dataset and its features.
-   Identify missing values, outliers, and data imbalances.

### 2. Data Preprocessing

-   Handle missing values and clean the data.
-   Convert categorical variables to numerical using encoding techniques.
-   Standardize/normalize numerical features.

### 3. Model Building

-   Train various machine learning models such as:
    -   Logistic Regression
    -   Random Forest
    -   AdaBoost
    -   SVC
-   Use cross-validation to evaluate model performance.

### 4. Model Evaluation

-   Assess the models using metrics such as:
    -   Accuracy
    -   Precision
    -   Recall
    -   F1 Score

### 5. Insights and Recommendations

-   Interpret model results.
-   Provide actionable insights for business decisions.

## Installation and Setup Instructions

### Step 1: Arrange the Provided Files

Place the following files in the same directory:

-   `Customer Churn Prediction.ipynb`
-   `WA_Fn-UseC_-Telco-Customer-Churn.csv`

### Step 2: Set Up the Environment

-   Install Python (version 3.7 or higher) and Jupyter Notebook.
-   There is a requirements.txt folder for installing the required libraries, run: pip install -r requirements.txt (If you face any problems, please feel free to reach us)
-   Ensure required libraries are installed.

### Step 3: Execute the Code

1. Open Jupyter Notebook and navigate to the project directory.
2. Open `Customer Churn Prediction.ipynb`.
3. Parameter Tuning code sections (Randomized & GridSearch) are commented for saving your time. We run the models with the best parameters according to results. You can uncomment and try it if you desire.
4. Run all cells sequentially to execute the code.

## Troubleshooting

-   Ensure files are correctly placed in the same directory.
-   Install missing libraries using `pip install`.
-   Restart the Jupyter Notebook kernel if needed.

## Results

The performance of the trained models is evaluated using multiple metrics, including:

-   Accuracy
-   Precision
-   F1 Score
-   Model Comparison

The models' performance metrics are compared to identify the best-performing model for predicting customer churn. The detailed evaluation is available in the notebook.
