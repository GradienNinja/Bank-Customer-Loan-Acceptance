## Project Overview

This project builds and compares two machine learning models to predict whether a bank customer will accept a personal loan offer.

### Dataset
- **Source:** Kaggle - Bank Personal Loan Modelling
- **Samples:** 5000 observations
- **Features:** 14 variables (Age, Income, Family, Education, etc.)
- **Target:** Personal Loan (Binary: Accept/Reject)

### Models Built

1. **Decision Tree Classifier**
   - Test Accuracy: 98%
   - Class 1 Recall: 87%
   - File: `decision_tree_model.pkl`

2. **Support Vector Machine (RBF Kernel)**
   - Test Accuracy: 98%
   - Class 1 Recall: 78%
   - File: `svm_model.pkl`

### Results
Decision Tree outperforms SVM with better recall for loan accepters (87% vs 78%), making it more suitable for identifying potential customers.

### Files
- `decision_tree_model.pkl` Trained Decision Tree model
- `svm_model.pkl` Trained SVM model
- `scaler.pkl` StandardScaler for feature scaling




### Key Insights
- Age and Experience are highly correlated (1.0)  only one needed
- Decision Tree is the better model for this problem
- 98% accuracy on test data
- Model can effectively identify loan accepters

