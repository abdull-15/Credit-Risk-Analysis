# Unit-11-Classification

## Background

Auto loans, mortgages, student loans, debt consolidation ... these are just a few examples of credit and loans that people are seeking online. Peer-to-peer lending services such as LendingClub or Prosper allow investors to loan other people money without the use of a bank. However, investors always want to mitigate risk, so you have been asked by a client to help them use machine learning techniques to predict credit risk.

In this assignment, you will build and evaluate several machine-learning models to predict credit risk using free data from LendingClub. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so you will need to employ different techniques for training and evaluating models with imbalanced classes. You will use the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques

## Conclusion
---

#### Ensemble
In this section, you will train and compare two different ensemble classifiers to predict loan risk and evaluate each model. You will use the "Balanced Random Forest Classifier", and the "Easy Ensemble Classifier".

##### Results



Which model had the best balanced accuracy score?

* The model with the best balanced accuracy score was the Easy ensemble Classifier. It had a balance accuracy score of 93.16%

Which model had the best recall score?

* The Easy Ensemble classifier model also had a higher recall score which was 94%. The Balanced Random Forest Classifier had a recall score of 87%

Which model had the best geometric mean score?

* The Easy Ensemble classifier model also had the higher Geometric Mean Score. The GMS for The Easy ensemble classifier was 93%, while the GMS for the Balanced Random forest classifier was 78% 

What are the top three features?

*   The top three features are "total_rec_prncp", "total_pymnt", and "total_pymnt_inv'

#### Resampling

You will use the "imbalanced learn library" to resample the LendingClub data and build and evaluate logistic regression classifiers using the resampled data.

##### Results


Which model had the best balanced accuracy score?

* The model that had the best balanced accuracy score was the Random Oversampled model. The balanced score was 84.18% 

Which model had the best recall score?

* The model that had the best recall score was  also the Random Oversampled model. The recall score was 85% 

Which model had the best geometric mean score?

* The model that had the best Geometric Mean Score was also the Random Oversampled model. GMS was 84%
