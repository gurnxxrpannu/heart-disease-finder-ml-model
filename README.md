# 🫀 Heart Disease Prediction Model (End-to-End ML Project)

This is a machine learning project that predicts the presence of heart disease based on medical data. The model is trained and evaluated using various ML algorithms and includes preprocessing, hyperparameter tuning, and visualization — all inside a single Jupyter Notebook.

---

## 📌 Features

- ✅ End-to-end model training in Jupyter Notebook
- ✅ Data analysis and preprocessing
- ✅ Trained with:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Random Forest Classifier
- ✅ Model evaluation using:
  - Accuracy, Precision, Recall, F1-score
  - Confusion Matrix (Seaborn heatmap)
  - ROC Curve (via `RocCurveDisplay`)
- ✅ Cross-validation using `cross_val_score`
- ✅ Hyperparameter tuning with:
  - `RandomizedSearchCV`
  - `GridSearchCV`
- ✅ Model export via `joblib` / `pickle`
- ✅ Conda environment file (`environment.yml`) for easy setup

---

## 🧠 Dataset

This project uses a heart disease dataset with features like:

- Age, Sex, Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Max Heart Rate Achieved
- Exercise Induced Angina
- ST Depression
- Target (0: No Heart Disease, 1: Heart Disease)

📁 Dataset file: `heart-disease.csv`

---


📈 Model Evaluation
Models are evaluated using:

Accuracy

Precision, Recall, F1-score

Confusion Matrix (Seaborn heatmap)

ROC Curve (via RocCurveDisplay)

Cross-Validation Score

🧪 Example Output
Confusion matrix with seaborn heatmap

ROC curves for classification models

Cross-validation accuracy scores

Best hyperparameters via RandomizedSearchCV / GridSearchCV
