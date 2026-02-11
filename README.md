# ❤️ Heart Disease Prediction (Ensemble ML Pipeline)

A complete **end-to-end machine learning pipeline** for heart disease
prediction using ensemble learning. Built for real use --- not demos.

Includes: - Data preprocessing - Feature scaling - Multiple base
models - Ensemble voting - Evaluation - Visualization - Feature
importance - Submission generation

------------------------------------------------------------------------

## 📁 Project Structure

    Heart_Disease_Prediction/
    │
    ├── Heart_Disease_Prediction_Model_Colab.ipynb
    ├── train.csv
    ├── test.csv
    ├── submission.csv
    └── README.md

------------------------------------------------------------------------

## 🚀 Workflow

1.  Load data from CSV\
2.  Handle missing values\
3.  Scale features\
4.  Train multiple models\
5.  Generate ensemble predictions\
6.  Evaluate performance\
7.  Visualize predictions\
8.  Analyze feature importance\
9.  Generate submission file

------------------------------------------------------------------------

## 🧠 Models Used

-   Gradient Boosting Classifier\
-   Random Forest Classifier\
-   Extra Trees Classifier\
-   AdaBoost Classifier\
-   Logistic Regression

### Ensemble Method

**Soft Voting (Probability Averaging)**\
Predictions are combined using weighted probabilities for better
generalization and stability.

------------------------------------------------------------------------

## 🔧 Preprocessing

-   Missing values → Median filling\
-   Scaling → RobustScaler\
-   Feature consistency validation\
-   Data leakage prevention

------------------------------------------------------------------------

## 📂 Data Format

### train.csv

-   `id` (optional)
-   13 medical features
-   `Heart Disease` (target: 0 or 1)

### test.csv

-   `id`
-   13 medical features

### Output

    id,Heart Disease
    630000,0
    630001,1

------------------------------------------------------------------------

## 📊 Evaluation

-   Cross-validation AUC
-   Individual model performance comparison
-   Ensemble performance comparison
-   Probability distribution visualization
-   Feature importance analysis

------------------------------------------------------------------------

## 🩺 Features Used

1.  Age\
2.  Sex\
3.  Chest Pain Type\
4.  Blood Pressure\
5.  Cholesterol\
6.  FBS over 120\
7.  EKG Results\
8.  Max Heart Rate\
9.  Exercise Angina\
10. ST Depression\
11. ST Slope\
12. Number of Vessels (Fluoro)\
13. Thallium

------------------------------------------------------------------------

## ▶️ How to Run

### Google Colab

1.  Upload notebook\
2.  Mount Google Drive\
3.  Place `train.csv` and `test.csv` in Drive\
4.  Update file paths\
5.  Run all cells

------------------------------------------------------------------------

## 🛠 Troubleshooting

-   File not found → Check Drive paths\
-   Feature mismatch → Ensure same columns\
-   Memory issue → Reduce model size\
-   Low accuracy → Check data quality

------------------------------------------------------------------------

## 🎯 Purpose

This project is designed for: - ML practice - Competitions - Portfolio
projects - Real pipeline demonstration - End-to-end ML system design

------------------------------------------------------------------------

## 📌 Notes

This is a **pipeline notebook**, not just a model file. It
demonstrates: - Model engineering - ML system design - Ensemble
learning - Data pipeline structuring - Production-style workflow
