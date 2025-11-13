# BodoLand

This repository contains analysis and model evaluation for a synthesized dataset derived from field data collected in the Bodoland Territorial Region (BTR) of Assam, India.

## Dataset

- **File**: `new_synthetic_data_credit_assigned.csv`
- **Description**: A synthetic version of the original dataset collected during a field visit. It has been curated to preserve key characteristics for analysis and model development.

## Model Evaluation

The following Jupyter notebooks are used to train and evaluate different machine learning models on the dataset:

### 1. LLM-ARFE (Random Forest)
- **Notebook**: `rf_onbodo.ipynb`
- **Metrics**: Accuracy, Precision, Recall, F1-score
- **Visuals**: ROC Curve, Precision-Recall (PR) Curve

### 2. K-Nearest Neighbors (KNN)
- **Notebook**: `knn.ipynb`
- **Metrics**: Accuracy, Precision, Recall, F1-score
- **Visuals**: ROC Curve, Precision-Recall (PR) Curve

### 3. Logistic Regression (LR)
- **Notebook**: `logit.ipynb`
- **Metrics**: Accuracy, Precision, Recall, F1-score
- **Visuals**: ROC Curve, Precision-Recall (PR) Curve

### 4. Support Vector Classifier (SVC)
- **Notebook**: `svc.ipynb`
- **Metrics**: Accuracy, Precision, Recall, F1-score
- **Visuals**: ROC Curve, Precision-Recall (PR) Curve

## Robustness Testing

To study model performance under different conditions:

- **Notebook**: `diff_noise_lvl_and_varying_dataset.ipynb`
- **Purpose**: Examines how accuracy, precision, recall, and F1-score vary with:
  - Different noise levels
  - Varying dataset sizes
- **Models Compar
