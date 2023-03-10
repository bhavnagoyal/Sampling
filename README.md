# Sampling_Assignment

Various ML models are applied on the dataset to find out which Model,sampling technique combination
gives us the best accuracy.


Following 5 sampling Techniques were used:

1. Random Under Sampler (Sampling1)
2. Random Over Sampler (Sampling2)
3. SMOTE (Sampling3)
4. TOMEK links (Sampling4)
5. Near Miss (Sampling5)


The Sample size was calculates using the following formula: n = Z^2(p(1 – p)/m^2) where: 
n = sample size
Z = z-value (for 99% confidence interval, Z = 2.576)
p = proportion of the minority class (taken as 0.5 for a balanced dataset)
m = margin of error (taken as 0.05 for a sample size of 1000)


Following 5 models were applied on the sampled dataset:
1. Logistic Regression (M1)
2. Decision Tree Classifier (M2)
3. Random Forest Classifier (M3)
4. Support Vector Classifier (SVC) (M4)
5. Extra Tree Classifier (M5)


RESULT

![](https://github.com/bhavnagoyal/Sampling/blob/9abd7fa711ee12566f5bb9ed1119da1c334eb3eb/result.png)





