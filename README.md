Predicting Diabetes Diabetes Mellitus is an increasingly prevalent chronic disease characterized by the body’s inability to metabolize glucose. Building Machine Learning model to predict whether a person has diabetes or not, based on information about the patient such as blood pressure, body mass index (BMI), age, etc.

The model is to help physicians in predicting patients with future occurrence of diabetes and providing necessary preventive interventions. Fasting blood glucose, body mass index, high-density lipoprotein, and triglycerides were the most important predictors in these models. Compare performance of classification algorithms

Dataset source: The data was collected and made available by “National Institute of Diabetes and Digestive and Kidney Diseases” as part of the Pima Indians Diabetes Database.


Model Comments:
•1. The model returned a list of features that appear to explain majority of the variance in the dataset.

•2. After comparing these 3 models found that catbooster is best model with average accuracy score of 75 %.

•3. We will use this as a reference point to judge later models and reference this classification report for subsequent models.

Recommendations:
1. Insulin in blood decided type of diabetes, high insulin found in blood (as a medical reason insulin resistance) among type – II positive diabetes compare to other clustered people type – I.
2. Most important features are plas, mass, age, pedi , pres, skin, insu and then preg.
It is possible to predict with an accuracy of 75%
People with more number of pregnancies are more prone to diabetes.
People with high blood pressure and plasma glucose are more diabetic.
Age is also one factor in diabetes.
