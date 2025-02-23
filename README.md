# Project: Gold Recovery Prediction
Predicting gold recovery from ore using machine learning.

## Overview
This project focuses on predicting the efficiency of gold recovery from ore using machine learning. By analyzing raw data from the extraction and purification process, we aim to develop a model that optimizes production and improves process efficiency.

![gold_recovery_process1](https://github.com/user-attachments/assets/af3ecfea-7f4d-46dd-a665-1a31702e2547)


## Data
The dataset includes information on various metal concentrations and processing stages. The data is divided into:
- **Training set:** `gold_recovery_train.csv`
- **Test set:** `gold_recovery_test.csv`
- **Full dataset:** `gold_recovery_full.csv`

## Objectives
1. **Data Cleaning & Preprocessing**
   - Handle missing values and ensure consistency.
   - Verify the correctness of the provided recovery calculations.

2. **Exploratory Data Analysis (EDA)**
   - Examine changes in metal concentrations at different purification stages.
   - Compare feed particle size distributions.
   - Detect and remove anomalies in total substance concentrations.

3. **Model Development**
   - Train and compare multiple machine learning models (Linear Regression, Random Forest).
   - Use **sMAPE (symmetric Mean Absolute Percentage Error)** to evaluate model performance.
   - Select the best model for gold recovery prediction.

## Key Findings
- The **Random Forest Regressor** performed best with a final **sMAPE of 0.758** on the test set.
- The **Linear Regression model** had a lower sMAPE of **0.588**, but Random Forest provided a better balance of accuracy and generalization.
- The model effectively generalizes to unseen data, providing reliable predictions.
- Future improvements could include incorporating additional features.

### Model Performance (sMAPE)
| Model               | sMAPE Score |
|---------------------|------------|
| Linear Regression  | **0.588**   |
| Random Forest      | **0.758**   |
  

## Technologies Used
- Python (`pandas`, `numpy`, `matplotlib`, `scikit-learn`)
- Machine Learning (Regression models)
- Data Visualization (Histograms, Feature Importance, Model Performance Metrics)

## Future Updates
- Adding additional data visualizations for comparison
- Adding a feature importance plot to highlight key predictors in the Random Forest model 

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/project-gold-recovery.git
