# Module-17-Supervised-Machine-Learning-and-Credit-Risk

### Objectives/Overview

In this module, we use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. We also evaluate the performance of models to predict credit risk. <br/>
<br/>
### Resources

In this module, we utilized Jupyter and Python and Loan stats Lender Club data.<br/>
<br/>
### Analysis

# Credit Risk Resampling:

Naive Random Oversampling Results:<br/>
Accuracy score: 0.64<br/>
Confusion Matrix<br/>
TP: 67<br/>
FP: 6546<br/>
FN: 34<br/>
TN: 10558<br/>
<br/>
 
![1](https://github.com/Samira786/Module-17-Supervised-Machine-Learning-and-Credit-Risk/blob/master/linear_regression_salary/Resources/images/naive-1.png) <br/>
<br/>

SMOTE Oversampling Results:<br/>
Accuracy score: 0.65<br/>
Confusion Matrix<br/>
TP: 62<br/>
FP: 5317<br/>
FN: 39<br/>
TN: 11787<br/>
<br/>
 
![2](https://github.com/Samira786/Module-17-Supervised-Machine-Learning-and-Credit-Risk/blob/master/linear_regression_salary/Resources/images/Smote-2.png) <br/>
<br/>

Undersampling Results:<br/>
Accuracy score: 0.53<br/>
Confusion Matrix<br/>
TP: 67<br/>
FP: 10217<br/>
FN: 34<br/>
TN: 6887<br/>
<br/>

![3](https://github.com/Samira786/Module-17-Supervised-Machine-Learning-and-Credit-Risk/blob/master/linear_regression_salary/Resources/images/undersampling-3.png) <br/>

Combination Sampling (SMOTEENN):<br/>
Accuracy score: 0.65<br/>
Confusion Matrix<br/>
TP: 76<br/>
FP: 7566<br/>
FN: 25<br/>
TN: 9538<br/>
<br/>

![4](https://github.com/Samira786/Module-17-Supervised-Machine-Learning-and-Credit-Risk/blob/master/linear_regression_salary/Resources/images/combination-4.png) <br/>

Conclusion:<br/>
SMOTEENN would be the best model to use based on the highest risk percentage 75% in recall.<br/>
<br/>

# Credit Risk Ensemble

Balanced Random Forest Classifier Results:<br/>
Accuracy score(how correctly it classifies classes): 0.79<br/>
Confusion Matrix<br/>
TP: 57<br/>
FP: 1368<br/>
FN: 30<br/>
TN: 15750<br/>
<br/>
 
![5](https://github.com/Samira786/Module-17-Supervised-Machine-Learning-and-Credit-Risk/blob/master/linear_regression_salary/Resources/images/balanced-5.png) <br/>
<br/>

Easy Ensemble AdaBoost Classifier Results:<br/>
Accuracy score: 0.93<br/>
Confusion Matrix<br/>
TP: 79<br/>
FP: 979<br/>
FN: 8<br/>
TN: 16139<br/>
<br/>

![6](https://github.com/Samira786/Module-17-Supervised-Machine-Learning-and-Credit-Risk/blob/master/linear_regression_salary/Resources/images/easyensemble-6.png) <br/> 

Conclusion: <br/>
Easy Ensemble AdaBoost would be the best model to use. <br/>
<br/>
Easy Ensemble<br/>
High risk percentage - 91%<br/>
Low risk percentage – 94%<br/>
<br/>
Balanced Random Forest<br/>
High risk percentage - 66%. <br/>
Low risk percentage - 92%<br/>
<br/>
