# P1012-NC_Well_Arsenic
> Analyses used to determine if geologic factors and well construction characteristics can predict metal (arsenic and manganese) contamination and what at what thresholds are certain wells more at risk for contamination.

> All analyses in this respository are designated by their figure number or table number in the manuscript in parantheses.

In the instance that the files are unable to rendered the [NBViewer link](). 

# 1. Data Imputation
- Using random forest to impute the predictor variables and Quantile Regression Imputation of Left-Censored Data (QRILC) to impute each metal concentration

# 2. iAs/Mn Contamination Mapping (Figure 1)
- Visualizing iAs/Mn contamination by census tract in Union County, NC

# 3. Metal Prediction (Table 2 & 4, Table S1 & S2)
- Predicting arsenic and manganese contamination based on well data using supervised ML (random forest and support vector machine (SVM))

# 4. ML Visualizations (Figures 2-4)
- Confusion Matrix Figure (Figure 2)
  - Visualization of confusion matrix metrics from top performing supervised machine learning model across the use cases (SVM with a linear kernel)
- Variable Importance Plot (Figure 3)
  - Shows importance of each predictor from the top performing machine learning (ML) models (SVM with a linear kernel) for use case 1
- Decision Boundary Plot (Figure 4)
  - Visualization of two predictors to determine how well those variables could predict metal contamination
