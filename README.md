# Diabetes-XGBOOST
Diabetes predication  XGBOOSTED Hyperparameter model
This project focuses on predicting diabetes using various machine learning and deep learning techniques. The objective is to build accurate models to classify whether a patient has diabetes based on a given dataset.

## Dataset

The dataset used is the **Diabetes Dataset**, which contains several medical predictor variables (such as BMI, glucose level, insulin, etc.) and one target variable (whether the patient has diabetes or not).

## Models Used

- **XGBoost Classifier**
- **Random Forest Classifier**
- **Artificial Neural Network (ANN)**

Each of these models was trained and evaluated to compare their performance across key metrics such as accuracy, precision, recall, and F1 score.

## Results

- All models performed reasonably well in terms of overall accuracy.
- However, an important metric of concern is the **False Negatives** — cases where the model fails to detect diabetes in patients who actually have it.
- **False Negatives: 17**
  - This is a critical issue as failing to diagnose a diabetic patient can lead to serious health risks.
  - Future work will focus on reducing false negatives, possibly through:
    - Class weighting
    - Resampling techniques (e.g., SMOTE)
    - Threshold tuning
    - Ensemble methods

## Next Steps

- Fine-tune model thresholds to improve recall
- Use additional feature engineering or external data
- Implement more advanced ensemble strategies
- Explore cost-sensitive learning to penalize false negatives more heavily

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/REDWING007/Diabetes-XGBOOST.git
   cd diabetes-prediction
