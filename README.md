# Credit_Risk_Analysis

## Overview of the analysis: Explain the purpose of this analysis.
in this project, we will be analysing credit risk from, data in loan_stats.csv.  we will be using a variety of models to help predict whether or not someone is low risk or hgih risk for loans.  We will be building these models using imbalanced-learn and scikit-learn libraries to help evaluate them.  


## Results:

 - Naive Random Oversampling gave our balanced accuracy test of 66%.  The precision for the high risk is at 1% wioth the recall at 62%
![Naive Random Oversampling](https://github.com/Kwhitiak/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling%20.png)

 - the SMOTE OVersampling results came in with an accuracy score of 66% and 62% recall at 1% precision
![SMOTE](https://github.com/Kwhitiak/Credit_Risk_Analysis/blob/main/Images/SMOTE.png)


 - Undersampling results came in with an accuracy score of 66% and 69% recall at 1% precision.
![Undersampling](https://github.com/Kwhitiak/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)

 - The Combination results came in with an accuracy score of 54% with a recall of 75% at 1% presision.

![Combination](https://github.com/Kwhitiak/Credit_Risk_Analysis/blob/main/Images/Combination.png)

 - The Balanced Random Forest Classifier results came in with 78% accuracy with a recall of 70% at 3% precision

![Balanced Random Forest](https://github.com/Kwhitiak/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier.png)

 - Easy Ensemble AdaBoost Classifier results came in with 93% accuracy with a recall of 92% at 9% precision

![Easy Ensemble](https://github.com/Kwhitiak/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost%20Classifier.png)



## Summary:

in summary, the first four models used undersampling, oversampling and a combination of both to determine whish model is better at determining risk levels of individuals.  The last two models we used to help predict which loans are risky used resampling techniques using ensemble classifiers.  due to its high accuracy and good balance of precision and recall scores, the Easy Ensemble model is better at the rest at predictiing levels or risk.  
