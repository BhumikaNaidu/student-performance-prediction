#  Student Performance Prediction using Machine Learning

A machine learning project that predicts whether a student will pass or fail 
their final exam based on academic, social, and demographic factors.


 Project Overview

This project performs end-to-end machine learning on the UCI Student Performance 
dataset — from exploratory data analysis to model evaluation and visualization.
Built as part of my BCA Data Science program at SRM Institute of Science and Technology.


Dataset

- source:UCI Machine Learning Repository — Student Performance Dataset
- Records:395 students
- Features: 12 selected features including grades, study time, absences, 
  family background, and lifestyle factors
- Target: Pass (G3 ≥ 10) or Fail (G3 < 10)

 Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading and manipulation |
| Scikit-learn | ML models and evaluation |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots and heatmaps |
| Google Colab | Development environment |


Project Workflow

1. Data Loading— Loaded UCI dataset (395 records, 33 features)
2. EDA— Explored grade distributions, pass/fail ratio, study time patterns
3. Preprocessing — Label encoding, feature selection, train/test split (80/20), scaling
4. Modeling— Trained Decision Tree and KNN classifiers
5. Evaluation — Accuracy, precision, recall, F1 score, confusion matrix
6. visualization— Feature importance and model comparison charts

---

Results

| Model | Accuracy | Precision | Recall |
|-------|----------|-----------|--------|
| Decision Tree | 88%| 0.90 | 0.92 |
| KNN | ~81% | 0.82 | 0.86 |

Key Findings
- G2 (2nd period grade) is by far the strongest predictor of final performance
- G1 (1st period grade) is the second most important feature
- Past academic performance predicts future results better than social factors


