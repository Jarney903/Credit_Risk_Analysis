# Credit_Risk_Analysis
Module #17 Supervised Machine Learning

# Credit Risk Analysis

## Project Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.


## Resources
- Data Source: 2LoanStats_2019Q1.csv
- Software: Python 3.7, VS Code, sklearn library, sklearn library


## Analysis Results
The analysis for the six machine learning models including balanced accuracy, precision, and recall scores shows the following:

### 1 Naive Random Oversampling
![1](https://github.com/Jarney903/Credit_Risk_Analysis/blob/main/analysis/Fig_1.jpg)
Balanced Accuracy: 0.64
Precision: High/Low risk = .01 / 1.00
Recall: High/Low risk = .70/.59

### 2 SMOTE Oversampling
![2](https://github.com/Jarney903/Credit_Risk_Analysis/blob/main/analysis/Fig_2.jpg)
Balanced Accuracy: 0.66
Precision: High/Low risk = .01 / 1.00
Recall: High/Low risk = .63/.69

### 3 Undersampling
![3](https://github.com/Jarney903/Credit_Risk_Analysis/blob/main/analysis/Fig_3.jpg)
Balanced Accuracy: 0.54
Precision: High/Low risk = .01 / 1.00
Recall: High/Low risk = .69/.40

### 4 Combination (over & under)
![4](https://github.com/Jarney903/Credit_Risk_Analysis/blob/main/analysis/Fig_4.jpg)
Balanced Accuracy: 0.65
Precision: High/Low risk = .01 / 1.00
Recall: High/Low risk = .73/.57

### 5 Balanced Random Forest Classifier
![5](https://github.com/Jarney903/Credit_Risk_Analysis/blob/main/analysis/Fig_5.jpg)
Balanced Accuracy: 0.82
Precision: High/Low risk = .04 / 1.00
Recall: High/Low risk = .75 / .90

### 6 Ensemble Classifier
![6](https://github.com/Jarney903/Credit_Risk_Analysis/blob/main/analysis/Fig_6.jpg)
Balanced Accuracy: .93
Precision: High/Low risk = .07 / 1.00
Recall: High/Low risk = .91 / .94


## Analysis Summary
The following summary provides an analysis of the results:
    - Best Performance in Balanced Accuracy: Ensemble Classifier
    - Best Performance in Precision High Risk: All performed the same, very low
    - Best Performance in Precision Low Risk: All performed the same, very high
    - Best Performance in Recall High Risk: Ensemble Classifier
    - Best Performance in Recall Low Risk: Ensemble Classifier
Given the results from this analysis, the recomended model is Ensemble Classifier. 



    