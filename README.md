# Credit_Risk_Analysis #

## Overview of the analysis ##
-Is to use python to help predict credit risk using several methods.

## Results ##
### Oversampler ###
- The balanced accuracy score is 65%.
- The high_risk precision is about 4% only with about 67% sensitivity.
- Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 91%. 
-![Oversample](https://github.com/sheepesq/Credit_Risk_Analysis/blob/main/oversampler.png)

### SMOTE Oversampling ### 
-The restults are close to the Oversampler with an balanced_accuracy_score of 62%
-![SMOTE](https://github.com/sheepesq/Credit_Risk_Analysis/blob/main/smote.png)
### Undersampling ###
- balanced_accuracy_score of about 52%
- low risk is more accurate than the high risk due to sampling 

## Summary ##
- The models used to calculate the high risk in giving a person credit have low accuracy.
- Using the models in this module will not help a company figure out if a person is high risk or not.
