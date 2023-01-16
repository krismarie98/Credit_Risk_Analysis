# Credit_Risk_Analysis
## Overview of Analysis:
### The purpose of this challenge is to be able to predict whether a loan apllicant is low risk or high risk using supervised machine learning. To better explain, we will take the data that has been given and tell us if an applicant has been determined to low or high risk and train our application to make its own predictions.
## Results:
* Naive Random Oversampling Results: The accuracy for this is at 65.7%. The precision is 99%. The recall is at 71.% for high risk and 60.% for low risk, with an average of 60.%.
![image](https://user-images.githubusercontent.com/112527054/212568275-2c4556bf-8355-49db-8493-e6ccb4d4e85b.png)
* SMOTE Oversampling Results: The accuracy for SMOTE oversampling is 66.2%.  The precision is 99%. The recall is at 63.% for high risk and 69.% for low risk, with an average of 69.%.
![image](https://user-images.githubusercontent.com/112527054/212583605-68473604-18e2-4843-a3e3-9873c77af4f4.png)
* Undersampling Results: The accuracy for this is at 66.2%. The precision is at 99.%. The recall is at 69.% for high risk and 40.% for low risk with an average of 40.%
![image](https://user-images.githubusercontent.com/112527054/212568813-5afd0492-49a5-4d78-b0de-c8afb9d4f111.png)
* Over and Undersampling Results: The accuracy for this is at 54.4%. The precision is at 99%. The recall is at 72.% for high risk and 57% for low risk with and average of 57.%
![image](https://user-images.githubusercontent.com/112527054/212568996-958b2dc3-7676-45a3-b7fd-b97b7db7f592.png)
* Balanced Random Forest Classifier Results: The accuracy for this is at 77.4%. The precision is at 99%. The recall is at 66.% for high risk and 88% for low risk with and average of 88.%
![image](https://user-images.githubusercontent.com/112527054/212569465-fb5d6c8c-cf03-43be-927d-f5f0757fdcb1.png)
* Easy Ensemble Classifer Results:The accuracy for this is at 93.1%. The precision is at 99%. The recall is at 92.% for high risk and 94% for low risk with and average of 94.%
![image](https://user-images.githubusercontent.com/112527054/212569538-ab805459-722c-41be-b96a-69b1c3755cd3.png)
## Summary:
### For this module challenge we used several different approaches to train and test data in order to decide if an applicant is high risk or low risk. In the first approaches we use the undersampling and oversampling apporaches. In the next steps, the easy ensemble and balanced random forest apporach is used. In this case I think the best approach is the easy ensemble approach it does have a high accuracy. Additionally, the results are good overall in recall and precison. In this case precision is important to see how accurate the application is.
