# svm-breast-cancer-prediction
# Task 7: Support Vector Machines (SVM) - Elevate Labs AI & ML Internship

##  Objective:
Use SVMs for linear and non-linear classification using real-world binary datasets.

## Tools Used:
- Python
- Scikit-learn
- NumPy
- Matplotlib

##  What I Did:
- Loaded the Breast Cancer dataset using `sklearn.datasets`.
- Preprocessed the data with `StandardScaler` to normalize features.
- Split the dataset into training and testing sets.
- Trained SVM using **RBF kernel** with parameters `C=1.0` and `gamma='scale'`.
- Evaluated the model using accuracy, confusion matrix, and classification report.

## Key Concepts Learned:
- Support Vectors
- Margin maximization
- Kernel trick (RBF)
- Hyperparameter tuning (`C`, `gamma`)
- Overfitting handling using regularization

##  Dataset:
- Used `load_breast_cancer()` dataset from `sklearn.datasets`

## Output:
Achieved high classification accuracy on the test set for Breast Cancer prediction.

---
