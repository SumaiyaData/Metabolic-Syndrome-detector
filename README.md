# Metabolic-Syndrome-detector
**Metabolic Syndrome Prediction**
A machine learning project to predict Metabolic Syndrome using clinical and demographic features. The project demonstrates end-to-end ML pipelines including preprocessing, outlier handling, encoding, scaling, and model training.

**Project Highlights**

✅ Data Cleaning & Imputation: Handles missing values with median and most frequent strategies

✅ Outlier Handling: Caps outliers using IQR and Z-score methods

✅ Feature Encoding: One-hot encoding for categorical variables

✅ Scaling: Flexible scaling using MinMax, Standard, and Yeo-Johnson transformations

✅ Models: Logistic Regression and Random Forest with class balancing

✅ Evaluation: Accuracy, confusion matrix, precision, recall, F1-score, and cross-validation

✅ Pipeline Export: Preprocessing + model pipelines saved with pickle for easy deployment

**Performance**
| Model               | Accuracy | Precision (Class 1) | Recall (Class 1) | F1-Score (Class 1) |
| ------------------- | -------- | ------------------- | ---------------- | ------------------ |
| Logistic Regression | 0.85     | 0.73                | 0.85             | 0.79               |
| Random Forest       | 0.88     | 0.85                | 0.78             | 0.81               |

**Dataset**
Provided in the data/ folder: Metabolic Syndrome.csv
