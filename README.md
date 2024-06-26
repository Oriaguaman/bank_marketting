# Bank Marketing Dataset Analysis done by Blessing Oriaguaman

This repository contains Jupyter Notebook files for analyzing the Bank Marketing dataset using different class imbalance techniques and employing five machine learning algorithms:

1. K Nearest Neighbor
2. Decision Tree
3. Logistic Regression
4. Gradient Boosted Regression Tree
5. Random Forest Tree

## File Structure

- **`bank_marketting_smote.ipynb`**: Jupyter Notebook analyzing the Bank Marketing dataset using the SMOTE (Synthetic Minority Over-sampling Technique) technique for handling class imbalance.
- **`bank_marketting_UnderSamp.ipynb`**: Jupyter Notebook analyzing the Bank Marketing dataset using the undersampling technique for handling class imbalance.
- **`bank_marketting_OverSamp.ipynb`**: Jupyter Notebook analyzing the Bank Marketing dataset using the oversampling technique for handling class imbalance.
- **`bank_marketting_without_class_balancing.ipynb`**: Jupyter Notebook analyzing the Bank Marketing dataset without handling class imbalance.

For each class imbalance technique, there are two corresponding files:

- **`bank_marketting_smote-Cross_validation.ipynb`**: Jupyter Notebook with cross-validation included for evaluating model performance.
- **`bank_marketting_UnderSamp-Cross_validation.ipynb`**: Jupyter Notebook with cross-validation included for evaluating model performance.
- **`bank_marketting_OverSamp-Cross_validation.ipynb`**: Jupyter Notebook with cross-validation included for evaluating model performance.

Each notebook includes code for data preprocessing, model training, evaluation, and visualization.

## Dataset
The Bank Marketing dataset contains data on direct marketing campaigns of a Portuguese banking institution. It includes various features such as age, job, marital status, education, etc., and the target variable indicating whether the client subscribed to a term deposit.

## Class Imbalance Techniques
- **SMOTE (Synthetic Minority Over-sampling Technique)**: This technique generates synthetic samples for the minority class to balance the class distribution.
- **Undersampling**: This technique randomly removes samples from the majority class to balance the class distribution.
- **Oversampling**: This technique randomly duplicates samples from the minority class to balance the class distribution.
