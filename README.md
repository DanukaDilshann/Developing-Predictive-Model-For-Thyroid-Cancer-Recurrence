# Studying Recurrence of Well-Differentiated Thyroid Cancer

## Overview
This project aims to develop a predictive model for the recurrence of well-differentiated thyroid cancer using machine learning techniques. The dataset includes 17 variables from 383 patients, collected over a 15-year period.

## Objectives
- Develop a predictive model for thyroid cancer recurrence.
- Enhance diagnostic accuracy and early detection.
- Improve patient management and treatment planning.

## Dataset
The dataset contains the following variables:
- Age
- Gender
- Smoking history
- Thyroid function
- Cancer stage
- Treatment response
- Recurrence status
  
## Data Preprocessing
- No missing values were found.
- 19 duplicate records were removed, leaving **364 unique patient records**.
  - #### Handling Data Imbalance
  The dataset exhibited an imbalance between the number of recurrent and non-recurrent cases. 
  To address this, we employed the Synthetic Minority Over-sampling Technique (SMOTE). SMOTE synthesizes new examples from the minority class to 
  achieve a balanced dataset, improving the performance of the machine learning models.
  - #### One-Hot Encoding
   To handle categorical variables, we applied one-hot encoding to convert them into a format suitable for machine learning algorithms.
## Machine Learning Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest

## Key Findings
- The SVM model achieved a 97% accuracy level, surpassing the accuracies of the other 
models.
- Additionally, our findings reveal a significant association between smoking and thyroid 
cancer recurrence. Patients who smoke have a higher likelihood of experiencing a 
recurrence.
- Further, patients with high stage thyroid cancer experience a lower response rate to the 
treatment compared to the other stage patients. 
- Moreover, patients with cancer present in multiple locations have a higher risk of thyroid 
cancer recurrence.
- However, there is no observed association between the type of thyroid function 
(hypothyroidism or hyperthyroidism) and the recurrence of thyroid cancer.
- Furthermore, younger patients show a notably better response to treatment compared to 
other age groups.


## Repository Structure
- `Data/`: Dataset [Thyroid Cancer Recurrence](https://www.kaggle.com/datasets/jainaru/thyroid-disease-data)
- `Notebooks/`: Jupyter notebooks for data analysis.
- `Reports/`: Model Comparisons.

## How to Use
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebooks in the `Notebooks/` directory.
