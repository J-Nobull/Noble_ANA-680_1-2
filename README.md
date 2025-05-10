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

## Task Description

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
