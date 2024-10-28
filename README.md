# Headstarter Bonus Project

## Table of Contents
- [Preprocessing](#preprocessing)
- [Feature Engineering](#feature-engineering)
- [Models and Performance](#models-and-performance)
  - [Headstarter_Bonus_Project_1](#headstarter_bonus_project_1)
  - [Headstarter_Bonus_Project_2](#headstarter_bonus_project_2)
- [Final Benchmarks](#final-benchmarks)


## Preprocessing

Effective preprocessing is crucial for enhancing model performance. The following preprocessing steps were applied across the projects:

- **One-Hot Encoding (`get_dummies`)**: Transformed categorical variables into a binary matrix.
- **Binary Encoding**: Reduced dimensionality for high-cardinality categorical features.
- **Removed Unnecessary Columns**: Eliminated irrelevant or redundant features to streamline the dataset.
- **SMOTE (Synthetic Minority Over-sampling Technique)**: Addressed class imbalance by generating synthetic samples for the minority class.

## Feature Engineering

- **Population to Amount Ratio**: Created a new feature by calculating the ratio of population to amount, providing additional insights for the models.

## Models and Performance

### Headstarter_Bonus_Project_1

**Best Performing Models:**

1. **Gaussian Naive Bayes (GaussianNB)**
   - **Precision**: 0.23
   - **Recall**: 0.47
   - **Accuracy**: 99.2%
   - **Description**: Achieved a balanced precision and recall, making it a reliable choice for scenarios requiring equilibrium between false positives and false negatives.

2. **Logistic Regression**
   - **Precision**: 0.06
   - **Recall**: 0.75
   - **Accuracy**: 95.27%
   - **Description**: Exhibited the best recall, effectively identifying true positive cases but with lower precision.

3. **Voting Classifier**
   - **Precision**: 0.16
   - **Recall**: 0.61
   - **Accuracy**: 98.6%

**Preprocessing Techniques:**
- One-Hot Encoding
- Population to Amount Ratio Feature Engineering
- Column Removal
- SMOTE

### Headstarter_Bonus_Project_2

**Best Performing Model:**

1. **XGBoost (with SMOTE)**
   - **Precision**: 0.31
   - **Recall**: 0.32
   - **Accuracy**: 99.5%

**Preprocessing Techniques:**
- One-Hot Encoding
- Binary Encoding
- Population to Amount Ratio Feature Engineering
- Column Removal
- SMOTE

**Final Voting Classifier:**
- **Precision**: 0.22
- **Recall**: 0.43
- **Accuracy**: 99.2%

## Final Benchmarks

After evaluating all models and preprocessing strategies, the final performance metrics are summarized as follows:

**Best Performing Model:**
 **XGBoost (with SMOTE)**
   - **Precision**: 31%
   - **Recall**: 32%
   - **Accuracy**: 99.5%

**Higest Benchmarks Achieved (Different Models):**
- **Accuracy**: 99.2%
- **Precision**: 31%
- **Recall**: 75%


