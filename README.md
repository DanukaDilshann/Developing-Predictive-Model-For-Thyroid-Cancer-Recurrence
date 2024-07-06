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
  
## Machine Learning Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest

## Key Findings
- SVM model achieved the highest accuracy (97%).
- Smoking is a significant risk factor for recurrence.
- Higher cancer stages are associated with lower treatment response rates.
- Multifocal cancer increases the risk of recurrence.

## Repository Structure
- `Data/`: Dataset and preprocessing scripts.
- `Notebooks/`: Jupyter notebooks for data analysis.
- `Models/`: Saved models.
- `Reports/`: Reports and visualizations.
- `Scripts/`: Python scripts for data processing and model training.

## How to Use
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebooks in the `Notebooks/` directory.
