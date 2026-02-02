# Task 11 – SVM: Breast Cancer Classification

## Objective
To build and evaluate Support Vector Machine (SVM) models for breast cancer
classification using linear and RBF kernels, and improve performance using
hyperparameter tuning.

## Dataset
- Breast Cancer Wisconsin Dataset
- Source: scikit-learn (load_breast_cancer)
- Target:
  - 0 → Malignant
  - 1 → Benign

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## Steps Performed
1. Loaded breast cancer dataset
2. Split data into training and testing sets
3. Applied StandardScaler for feature normalization
4. Trained baseline SVM with linear kernel
5. Trained SVM with RBF kernel
6. Tuned hyperparameters using GridSearchCV
7. Evaluated best model using accuracy and classification report
8. Plotted ROC curve and calculated AUC
9. Saved trained SVM model

## Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score
- ROC Curve & AUC

## Files
- Task-11.ipynb
- svm_breast_cancer_model.pkl
- README.md

## Conclusion
The tuned SVM model with RBF kernel achieved strong classification performance.
Feature scaling and hyperparameter tuning significantly improved results.
