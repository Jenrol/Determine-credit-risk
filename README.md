# Determine-credit-risk
# Data Science and Analytics Code README

## Introduction
This repository contains code for performing data analysis and modeling on a dataset named "credit_data.csv." The dataset contain information related to credit risk assessment, and the code performs various data preprocessing, exploratory data analysis, and modeling tasks to determine credit risk of customer.

### 1. Set Working Directory
Ensure that you set your working directory to the location where the "credit_data.csv" file is located. You can do this by modifying the following code snippet in the R script to point to your file's directory:

```r
setwd("C:/users/jenro/oneDrive/Desktop/ABOSEDE/cover letters/Job Applications/Gen Re")
```

### 2. Import the Dataset
The code imports the dataset from the CSV file "credit_data.csv." Make sure you have the dataset file in the specified directory or modify the code to provide the correct path.

### 3. Data Exploration
The code performs data exploration to understand the dataset's structure and content. It includes:
- Displaying the first few rows of the dataset.
- Providing a summary of the dataset's structure.
- Checking for missing values and reporting columns with missing data.

### 4. Data Transformation
The code performs data transformation steps, including:
- Replacing values in the "credit_risk" column to convert it into a binary variable.
- Encoding categorical variables using one-hot encoding.

### 5. Descriptive Analysis and Visualization
The code generates visualizations and analyses to gain insights into the dataset. This includes:
- Creating bar charts to show the distribution of account status and employment.
- Calculating and comparing total credit amounts for different employment and account status categories.
- Creating a boxplot to compare the distribution of credit amounts between good and bad credit risk categories.
- Generating histograms to visualize the distribution of age, credit amount, and duration.
- Creating scatter plots to explore relationships between age, credit amount, and duration.

### 6. Modeling
The code performs logistic regression and XGBoost modeling to predict credit risk. It includes:
- Data splitting into training and test datasets.
- Logistic regression modeling with evaluation metrics.
- XGBoost modeling with evaluation metrics.

### 7. Evaluation
The code evaluates the models and reports performance metrics such as accuracy, precision, recall, and F1-score for both logistic regression and XGBoost models. Additionally, it visualizes feature importance using SHAP (SHapley Additive exPlanations) values.

## Conclusion
This README provides an overview of the code's functionality and usage instructions. You can run the code in an R environment after setting the working directory and ensuring that the dataset file is available. The code aims to provide insights into credit risk assessment and demonstrates the use of different data analysis and machine learning techniques for predictive modeling.
