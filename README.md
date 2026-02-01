# Obesity Risk Prediction Using Ensemble Learning

## Overview
This project predicts obesity risk levels based on individual lifestyle and health-related factors using machine learning. Multiple classification models are trained and combined using ensemble techniques to improve prediction performance.

This project was developed as part of an AI/ML core induction assignment.

---

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Google Colab

---

## Models Used
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

A soft-voting ensemble approach is used to combine predictions from all models.

---

## Dataset
- The dataset contains approximately 21,000 records with 16 input features.
- The target variable represents obesity risk categories.
- The dataset is stored in the `data/` folder as `obesity_dataset.csv`.

---

## How to Run
1. Open `obesity_ensemble_model.ipynb` in Google Colab or Jupyter Notebook.
2. Ensure the dataset path is set to `data/obesity_dataset.csv`.
3. Run all cells sequentially.

---

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Model deployment

---

## Author
Jashan Singh Mehta
