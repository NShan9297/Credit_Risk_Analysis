# Credit_Risk_Analysis

# Results

## Balanced Random Forest 
Accuracy: 0.87311
![BalancedRandomForestC.png](https://github.com/NShan9297/Credit_Risk_Analysis/blob/main/Screenshots/BalancedRandomForestC.png)

## Easy Ensemble AdaBoost Classifier
Accuracy: 0.9424
![EasyEnsemble.png](https://github.com/NShan9297/Credit_Risk_Analysis/blob/main/Screenshots/EasyEnsemble.png)

## Naive Random Oversampling
Accuracy: 0.6504
![NaiveRandomOversampling.png](https://github.com/NShan9297/Credit_Risk_Analysis/blob/main/Screenshots/NaiveRandomOversampling.png)


## SMOTE Oversampling
Accuracy 0.6584
![SMOTE.png](https://github.com/NShan9297/Credit_Risk_Analysis/blob/main/Screenshots/SMOTE.png)

## Undersampling
Accuracy: 0.5767
![Undersampling.png](https://github.com/NShan9297/Credit_Risk_Analysis/blob/main/Screenshots/Undersampling.png)


## Combination Over/Under
Accuracy: 0.5767
![UnderOver.png](https://github.com/NShan9297/Credit_Risk_Analysis/blob/main/Screenshots/UnderOver.png)



# Summary
In choosing an accurate model for credit risk analysis, we are looking for a model that will be sensitive enough to catch any risky profiles, but precise enough to allow for the predicted positives to actually be positive. We should be looking for higher Recall and Higher Prec, with a high F1 score. We see balanced random forest and Easy Ensemble AdaBoost both have high F1 scores in comparison to all the other models that have low f1 scores. We see that the Easy Ensemble has the highest of all of the resampling models. This selection will be the best as it meets the above listed criterion. I would confidently advise that Easy Ensemble be used.