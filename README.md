# Credit-Card-Fraud-Detection (Kaggle)

1. Data is read from CSV into a dataset.
2. Calculated correlation matrix - None of the variables are correlated.
3. Since none of the variables are correlated, all variables are considered in classification algorithm.
4. Dataset is randomly divided into training and test dataset in 7:3 ratio.
5. Random Forest algorithm is applied on Training dataset by growing 100 trees.
6. Calculated predicted class for the test dataset using the Random Forest output.
7. Confusion matrix is derived for the dataset.
8. ROC Curve is plotted for the dataset.
9. ROC Curve is plotted using ROSE package and AUC is calculated
10. Oversampling, Undersampling, Both & ROSE techniques
