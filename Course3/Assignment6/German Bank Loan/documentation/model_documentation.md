# Model Documentation

## Introduction

This document provides comprehensive documentation of the machine learning models utilized in the German Bank Loan project. The goal of the project is to predict loan default based on historical customer data. Multiple machine learning algorithms were employed, each with its specific hyperparameters and preprocessing steps.

## Machine Learning Models

### 1. RandomForestClassifier

#### Hyperparameters:

- **n_estimators:** [10, 50, 100]
- **max_depth:** [None, 10, 20]
- **min_samples_split:** [2, 5, 10]
- **min_samples_leaf:** [1, 2, 4]

### 2. LogisticRegression

#### Hyperparameters:

- **C:** [0.001, 0.01, 0.1, 1, 10, 100]
- **penalty:** ['l1', 'l2']

### 3. DecisionTreeClassifier

#### Hyperparameters:

- **criterion:** ['gini', 'entropy']
- **splitter:** ['best', 'random']
- **max_depth:** [None, 10, 20]
- **min_samples_split:** [2, 5, 10]
- **min_samples_leaf:** [1, 2, 4]

### 4. GradientBoostingClassifier

#### Hyperparameters:

- **n_estimators:** [50, 100, 200]
- **learning_rate:** [0.01, 0.1, 0.2]
- **max_depth:** [3, 5, 7]
- **min_samples_split:** [2, 5, 10]

### 5. KNeighborsClassifier

#### Hyperparameters:

- **n_neighbors:** [3, 5, 7]
- **weights:** ['uniform', 'distance']
- **algorithm:** ['auto', 'ball_tree', 'kd_tree', 'brute']

## Preprocessing Steps

1. **Data Splitting:**
   - The dataset was split into training (80%) and testing (20%) sets.

2. **Handling Missing Values:**
   - Any missing values were addressed through appropriate imputation techniques.

3. **Feature Scaling:**
   - Numeric features were scaled to ensure uniformity across different scales.

4. **Categorical Encoding:**
   - Categorical variables were encoded using suitable methods, such as one-hot encoding.

5. **Hyperparameter Tuning:**
   - GridSearchCV was employed for hyperparameter tuning, optimizing each model for accuracy.

## Conclusion

This documentation provides a detailed overview of the machine learning models, hyperparameters, and preprocessing steps implemented in the German Bank Loan project. It serves as a reference for reproducibility and understanding the intricacies of the chosen models.