
# Task7-Elevate-labs

#  SVM Classifier – Breast Cancer Detection

## Task Overview
This is Task 7 of the AI & ML Internship.  
We implemented a Support Vector Machine (SVM) classifier using both linear and non-linear kernels on the Breast Cancer dataset.



## Steps Performed

1. Loaded Breast Cancer dataset using scikit-learn
2. Normalized the features using StandardScaler
3. Trained two SVM models:
   - Linear kernel
   - RBF (Radial Basis Function) kernel
4. Evaluated performance with confusion matrix, classification report
5. Tuned hyperparameters (C and gamma)
6. Used cross-validation for robust accuracy estimation



## Results

- Accuracy (Linear Kernel): Replace with your output
- Accuracy (RBF Kernel): Replace with your output
- Cross-Validation Accuracy (RBF): Replace with mean CV score



## Interview Questions & Answers

1. What is a support vector?  
   A data point that lies closest to the decision boundary and influences the position of the hyperplane.

2. What does the C parameter do?  
   It controls the trade-off between maximizing the margin and minimizing classification error. Lower C allows for a wider margin.

3. What are kernels in SVM?  
   Functions that allow the SVM to operate in a higher-dimensional space without explicitly computing coordinates (kernel trick).

4. Difference between linear and RBF kernel?  
   Linear kernel uses raw features, RBF maps features to a higher-dimensional space for non-linear separation.

5. Advantages of SVM?  
   High accuracy, effective in high-dimensional space, robust with clear margins.

6. Can SVMs be used for regression?  
   Yes, via SVR (Support Vector Regression).

7. What happens when data is not linearly separable?  
   Kernel functions like RBF are used to project data into higher dimensions where separation is possible.

8. How is overfitting handled in SVM?  
   By tuning C (regularization) and using proper kernels; large margins reduce overfitting.



## Tools Used

- Python
- scikit-learn
- NumPy, Matplotlib, Seaborn



# Files Included

- svm_classifier.ipynb — Jupyter Notebook with full code
- README.md — Task description and interview prep



