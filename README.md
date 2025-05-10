# Noble_ANA-680_Week_1_assignment 2
Building Classification Models

You are provided with a breast cancer dataset (Breast_Cancer_Data.csv) taken originally from the UCI data repository.  
https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original)

This dataset has approximately 683 patient data with 10 features and 1 class label describing whether the patient has cancer or not. Each row describes one patient, and the class column describes if the patient tumor is benign (label = 2) or malignant (label = 4). For this dataset, build eight(8) classification models (using Python and Scikit-learn) and tabulate the accuracy and confusion matrix obtained for each. Split the dataset such that the test data size is 25% of the total dataset.

Code each classification model in a separate python file. Then, tabulate the accuracy and confusion matrix in a Word document.

a. Logistic Regression
b. KNN (k=5)
c. Linear SVM (kernel = 'linear')
d. Kernel SVM (kernel = 'rbf')
e. Naïve Bayes
f. Decision Tree
g. Random Forest (estimators = 10)
h. XGBoost



# Noble\_ANA-680\_Week\_1\_Assignment\_2

**Building and Evaluating Classification Models**

## Overview

This assignment involves building and evaluating classification models using a breast cancer dataset originally sourced from
UCI Machine Learning Repository(https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28original%29)

The goal is to compare the performance of eight supervised learning algorithms using accuracy and confusion matrix metrics.

---

## Dataset Details

* **File:** `Breast_Cancer_Data.csv`
* **Instances:** \~683 patients
  * Each row represents one patient's diagnostic data.
* **Features:** 10 numeric attributes describing characteristics of cell nuclei
* **Target Label:**
  * `2` = Benign tumor
  * `4` = Malignant tumor

---

## 🔧 Task Description

1. **Build eight classification models** using Python and Scikit-learn.

2. **Split the dataset**:
   * Training set = 75%
   * Test set = 25%

3. **Evaluate each model**:
   * Calculate **accuracy**
   * Generate the **confusion matrix**

4. **Output**:
   * Each model's implementation should be in a **separate Python file**
   * Summarize results in a **Word document** including:
       * A table comparing the accuracy of all models
       * Confusion matrices for each model

---

## Models to Implement

a. **Logistic Regression**
b. **K-Nearest Neighbors (K=5)**
c. **Support Vector Machine (Linear Kernel)**
d. **Support Vector Machine (RBF Kernel)**
e. **Naïve Bayes**
f. **Decision Tree**
g. **Random Forest** (n\_estimators = 10)
h. **XGBoost**

---

## Notes

* Apply **data preprocessing** where necessary (e.g., label encoding, scaling).
* Ensure reproducibility by setting a random seed if applicable.
* You may include a README or comments within each Python script for clarity.
