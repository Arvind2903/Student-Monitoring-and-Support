# Student-Monitoring-and-Support

## Overview

This repository contains code and resources for a Kaggle competition focusing on student monitoring and support in higher education institutions. The competition task involves classifying students into three categories: dropout, enrolled, and graduate. The classes are coded as 0, 1, and 2 in the dataset. The evaluation metric for this competition is Mean F1-Score. The F1 score is used to measure accuracy, combining precision and recall equally. The dataset includes anonymized information about student demographics, academic paths, and performance.

## Dataset Description

The dataset is created from a higher education institution, incorporating information from various sources related to students enrolled in different undergraduate degrees. The dataset includes information known at the time of student enrollment, such as academic path, demographics, and socioeconomic factors, as well as academic performance at the end of the first and second semesters. The problem is formulated as a three-category classification task at the end of the normal duration of the course, with classes coded as 0, 1, and 2 in the dataset.

### Files

- **train.csv:** Training set
- **test.csv:** Test set
- **sample_submission.csv:** Sample submission file in the correct format

### Columns

- **Binary:** 'v_1', 'v_26', 'v_11', 'v_14', 'v_30', 'v_28', 'v_9', 'v_27'
- **Nominal:** 'v_32', 'v_4', 'v_3', 'v_20', 'v_21', 'v_18', 'v_25', 'v_12'
- **Ordinal:** 'v_31', 'v_15', 'v_19', 'v_13', 'v_33', 'v_17', 'v_29', 'v_23', 'v_6', 'v_24', 'v_10', 'v_5', 'v_22', 'v_0'
- **Ratio:** 'v_16', 'v_2', 'v_8', 'v_7', 'v_34', 'v_35', 'v_36', 'v_37', 'v_38', 'v_39', 'v_40'

## Usage

The code provided includes common preprocessing steps and models implemented for the competition. Preprocessing steps include data loading, handling missing values, and encoding categorical variables. Various models, including Adaboost, Gradient Boosting, Bagging, Decision Tree, Gaussian Naive Bayes, MLP, Random Forest, SGD, SVC, and XGBoost, are implemented with different hyperparameters. 

## Result
The best-performing model was XGBoost with 80% accuracy on the validation set and 77% accuracy on the unseen test set.

## Dependencies

- Python 3.x
- Required Python packages (specified in each script)
- Libraries: numpy, pandas, scikit-learn, scipy, imbalanced-learn, xgboost, matplotlib

## Extras
Feel free to check out the competition at https://www.kaggle.com/competitions/students-drop-out-prediction/ and explore others' solutions as well!
