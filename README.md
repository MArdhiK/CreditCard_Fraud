# Credit Card Fraud
I get the data from this : https://www.kaggle.com/kartik2112/fraud-detection.     
I just take the test data and it already consist of 555719 rows and 22 columns and with this dataset I created 7 models :
1. AdaBoost Classifier
2. Random Forest Classifier
3. Logistic Regression
4. Decision Tree Classifier
5. Gaussian Naive Bayes
6. XGB Classifier
7. LightGBM Classifier    

The best two are XGB and LightGBM with AUCScore 0.995 and 0.996 after tune it

----------------------------------------------------------------------------------

## Here's glimpse on my notebook
### Age Group Count and Gender
<img src=images/agegroup.png width=600>

### Day of Week Count and Gender
<img src=images/dayofweekgender.png width=600>

### Hour Count and Gender
<img src=images/hourgender.png width=600>

### Weekdays Transactions Percentages                   
<img src=images/weekdayspercentages.png width=400>    <img src=images/weekdaysfraud.png width=400>

### Hour Transactions Percentages
<img src=images/hourpercentages.png height=250>    <img src=images/hoursfraud.png height=250>

### Imbalance of Fraud
<img src=images/fraudgenderpercent.png width=600>

### Resampling Imbalance Data
<img src=images/smote.png width=600>

### ROCAUC Scores All Models
<img src=images/totalauc.png width=500>

### ROCAUC Scores XGB and LightGBM
<img src=images/tuneauc.png width=500>

## The Best One Amongs All is LightGBM with Tuning

### LGBM Confusion Matrix Tune and Non-Tune
<img src=images/lighttune.png width=400>     <img src=images/lightnontune.png width=400>

### LGBM Test Results
<img src=images/LGBMTune.png width=400>     <img src=images/LGBMNonTune.png width=400>


