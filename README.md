# Sampling techniques for making balanced samples from imbalanced dataset
## Introduction
For this task, we need to use different methods to extract samples from the credit card dataset. After creating these samples, we must use different classification models to correctly classify them and compare their accuracy using an accuracy matrix. The dataset contains 772 entries and 31 characteristics, and it is a binary classification dataset with 763 instances of one class and only 9 instances of the other. Because of this class imbalance,we first need to balance the dataset and we need to use effective sampling methods.

## Balancing the dataset
First we need to balance the ones and zeroes. For that, we can use either oversampling and undersampling.But for the given data, we have only 9 minority samples which will reduce the dataset drastically and thus,ML models will not be trained properly.So, for the above dataset,I have used oversampling which resulted in formation of new dataset which has equal zeroes and ones.
## Sampling Techniques
5 Sampling techniques were used on the balanced dataset which are:-

 1.Random Sampling
 
 2.Systematic Sampling
 
 3.Stratified Sampling
 
 4.Convinience Sampling
 
 5.SMOTE(Synthetic Minority Oversampling Technique) with random sampling
 
 ## Model Training

After appling the sampling techniques, the following 5 Machine Learning models are trained on the 5 samples obtained above-

1.Logistic Regression

2.Decision Tree

3.Support Vector Classification

4.KNeighborsClassifier

5.Random Forest Classifier







