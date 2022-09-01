# Credit_Risk_Analysis

## Overview of Analysis:
The purpose of this analysis is to determine if any given person in the dataframe is high or low risk. To do this we will be using supervised machine learning to intake the data and teach the machine how to best predict risk status for these loan applicants. 

## Results:
In order to test all the proper channels of this data we performed 6 different machine learning models. Below I will list these out and show the balanced accuracy score, precision, and recall scores for all of the machine learning models:

    - Naive Random Oversampling: 
        - Balanced Accuracy test is 67%
        - Precision - 
            - high risk 0.01
            - low risk 1.00
        - Recall -
            - high risk .62
            - low risk .65
    - Smote Oversampling:
        - Balanced Accuracy test is 63%
        - Precision - 
            - high risk 0.01
            - low risk 1.00
        - Recall -
            - high risk .62
            - low risk .64
    - Undersampling: 
        - Balanced Accuracy test is 63%
        - Precision - 
            - high risk 0.01
            - low risk 1.00
        - Recall -
            - high risk .59
            - low risk .43
    - Combination Sampling: 
        - Balanced Accuracy test is 51%
        - Precision - 
            - high risk 0.01
            - low risk 1.00
        - Recall -
            - high risk .59
            - low risk .43
    - Balanced Random Forest Classifier:
        - Balanced Accuracy test is 77%
        - Precision - 
            - high risk 0.03
            - low risk 1.00
        - Recall -
            - high risk .67
            - low risk .67
    - Ensemble AdaBoost Classifier: 
        - Balanced Accuracy test is 93%
        - Precision - 
            - high risk 0.09
            - low risk 1.00
        - Recall -
            - high risk .92
            - low risk .94

## Summary:
In conclusion it looks like the classifier models had the highest accuracy. Low risk results for precision stayed pretty similar between multiple of the models. It seems overall the classifier models returned the best results. 