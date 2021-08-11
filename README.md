# Credit_Risk_Analysis

## Overview of the Analysis

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.

In this project, I will be using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Then I will use the RandomOverSampler algorithm, SMOTE algorithm, ClusterCentroids algorithm and SMOTEENN algorithm to analyse a credit card data set from the LendingClub.  

Firstly, I will oversample the data using the algorithms. Secondly, I will undersample the data using the algorithms and then lastly, 
compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate the performance of these models.

### Resources

**Data Sources:** LoanStats_2019Q1.csv

**Code Files:** credit_risk_resampling.ipynb, credit_risk_ensemble.ipynb

**Software:** Numpy 1.19.2, Numby-base 1.19.2, Numpy doc 1.1.0, scipy 1.5.2, scikit-learn 0.23.2, imbalanced-learn,
Visual Studio Code 1.56.0, jupyter Notebook 6.3.0, Python 3.7.6 , Anaconda 4.8.5.

## Project Results

### Use Resampling Models to Predict Credit Risk 

![Oversampling Analysis](https://user-images.githubusercontent.com/81701640/128954890-a5264189-8e37-4cb4-856d-ad4c156540df.png)

See the summary below;

* Accuracy Score: 67%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 69%
* Recall Low Risk: 65%

![Undersampling Analysis](https://user-images.githubusercontent.com/81701640/128954903-40b090b0-8db3-4e6e-91a2-cf05f03ed6b8.png)

See the summary below;

* Accuracy Score: 52%
* Precision High Risk: 0%
* Precision Low Risk: 100%
* Recall High Risk: 61%
* Recall Low Risk: 44%

![SMOTE Analysis](https://user-images.githubusercontent.com/81701640/128954920-8cc9161f-a9be-4f43-b01d-05c16c756b29.png)

See the summary below;

* Accuracy Score: 67%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 70%
* Recall Low Risk: 64%

### Use the SMOTEENN algorithm to Predict Credit Risk 

![SMOTEENN Analysis](https://user-images.githubusercontent.com/81701640/128954934-996c7a47-19ee-4d22-b84c-8f95cf9d2c94.png)

See the summary below;

* Accuracy Score: 68%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 76%
* Recall Low Risk: 60%

### Use Ensemble Classifiers to Predict Credit Risk

![Ensemble Classifier_Random](https://user-images.githubusercontent.com/81701640/128954953-fc7b8108-fa0e-415f-9ad6-d0c9a71ff773.png)

See the summary below;

* Accuracy Score: 65%
* Precision High Risk: 56%
* Precision Low Risk: 100%
* Recall High Risk: 30%
* Recall Low Risk: 100%

![Ensemble Classifier_easy](https://user-images.githubusercontent.com/81701640/128954969-cbf01888-e6df-4b07-9d5f-25f6393b58f7.png)

See the summary below;

* Accuracy Score: 92%
* Precision High Risk: 6%
* Precision Low Risk: 100%
* Recall High Risk: 91%
* Recall Low Risk: 94%

## Project Summary

From the above analysis, the easy ensemble classifying has the highest accuracy score of 93%, with a recall rate of high risk at 91% and a recall rate of
low risk at 94%. 

This is the most effective of all the models used for this analysis, I will recommend this machine learning model for analysing and predicting credit risk.

**Nnaemeka Enukorah**

**August 14th, 2021**

