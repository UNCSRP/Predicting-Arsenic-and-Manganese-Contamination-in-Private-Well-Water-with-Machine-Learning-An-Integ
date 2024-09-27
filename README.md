# P1012-NC_Well_Arsenic

# 1. Data Imputation
- Using random forest to impute the predictor variables and Quantile Regression Imputation of Left-Censored Data (QRILC) to impute each metal concentration

# 2. Metal Prediction (Table 2 & 4, Table S1 & S2)
- Predicting arsenic and manganese contamination based on well data using supervised ML (random forest and support vector machine (SVM))

# 3. ML Visualizations (Figure 2-4)
- Confusion Matrix Figure (Figure 2)
  - Visualization of confusion matrix metrics from top performing supervised machine learning models across the use cases (SVM with a linear kernel)
  - This was done to visualize the generalizability of the models' accuracy after removing longitude and latitude in use case 2
- Variable Importance Plot (Figure 3)
  - Shows importance of each predictor for top performing machine learning (ML) models
- Decision Boundary Plot (Figure 4)
  - Visualization of two predictors in the top performing model to determine how well those variables could predict As well concentration
