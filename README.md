Project Overview:

This project, "Quantifying the Relationship Between Socioeconomic Status and Parent-child Attachment on Adolescents Through Machine Learning", investigates how different aspects of parent-child attachment relate to the socioeconomic status (SES) of adolescents.
Using survey data from 239 families (final dataset: 456 samples, 70 features after preprocessing), the study applied multiple machine learning models — Decision Tree, Random Forest, Logistic Regression, SVM, KNN, AdaBoost, and XGBoost — to classify SES.

Key Steps:

Data Preprocessing: Missing value imputation, outlier removal (Z-score), normalization (Z-score), and PCA for feature selection.
Handling Class Imbalance: Applied upsampling to improve model performance.
Model Evaluation: Used 5-fold cross-validation to assess accuracy and ROC AUC.

Key Findings:

XGBoost achieved the best performance after upsampling (Accuracy: 90.07%, ROC AUC: 0.9840).
Trust, communication, and alienation in maternal and paternal attachment were the most influential predictors of SES.
This research can help educators, policymakers, and mental health professionals design targeted interventions to support adolescents from diverse socioeconomic backgrounds.
