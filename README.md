# loan-prediction
Loan Prediction Project

Assignment for Data Mining Principles. The goal was to predict loan interest rates based on data presented. 

Summary:
1. Cleaned data & imputed null values by creating clusters and filling with mean of cluster
2. Ran EDA
3. Split test/train set
4. Ran 6 regression models on training set (linear regression, decision tree, random forest, gradient boosting, XGB regressor, and voting regressor)
5. Chose model with lowest test RMSE, that was also close to desired error (CV score) - XG BOOST
6. Applied XG Boost to Holdout data to predict loan interest rates
