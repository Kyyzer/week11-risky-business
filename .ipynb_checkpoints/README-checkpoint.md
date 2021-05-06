# Risky Business
---
## Summary
---
The following code attempts to predict credit risk by training and evaluating the performance of several machine learning models.

Below is a summary of balance accuracy scores and classification reports.

### Resampling
---
After resampling the data, each algorithm used a Logistic Regression with 'lbfgs' solver.
#### Simple Logistic Regression
**Balanced Accuracy Score:** 0.9893  

![](Resources/simple_log_reg.png)

#### Naive Random Oversampling
**Balanced Accuracy Score:** 0.9946  

![](Resources/random_over_sampler.png)

#### SMOTE
**Balanced Accuracy Score:** 0.9946  

![](Resources/random_over_sampler.png)

#### SMOTEENN
**Balanced Accuracy Score:** 0.9946  

![](Resources/random_over_sampler.png)

#### Cluster Centroid
**Balanced Accuracy Score:** 0.9933  

![](Resources/cluster_centroids.png)

### Ensemble Learners
---
Both ensemble algorithms were trained with n_estimators = 100.
#### Balanced Random Forest
**Balanced Accuracy Score:** 0.7888  

![](Resources/balanced_rf.png)

#### Easy Ensemble
**Balanced Accuracy Score:** 0.9313  

![](Resources/easy_ensemble.png)