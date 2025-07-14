# 🏆 INEGI GCIM Vegetation Mapping Challenge – 9th Place (out of 69 Teams) #


We participated in the INEGI GCIM Vegetation Mapping Challenge on Zindi and secured 9th place out of 69 teams on the private leaderboard.

## Problem Statement ##
The challenge was hosted by INEGI and the United Nations Committee of Experts on Global Geospatial Information Management (UN-GGIM). The goal was to predict the vegetation class for different regions in Mexico based on a variety of features, including elevation, soil type, climate, and land use.

Participants were required to train classification models that assign the correct vegetation class to each data point, contributing to better mapping of natural land cover and supporting global sustainability goals.

 ## Tools & Libraries Used ##
Python, Pandas, NumPy

scikit-learn, LightGBM, XGBoost, CatBoost

Seaborn, Matplotlib

Models: RandomForest, BaggingClassifier, IsolationForest

 ## Data Preprocessing ##
Label Encoding for categorical columns

Imputation for missing values using SimpleImputer

Feature selection and scaling using Pipeline

Optional PCA for dimensionality reduction

Dataset split with StratifiedKFold for balanced evaluation

 ## Models Trained ##
 
We trained and compared several models:

✅ LightGBM

✅ XGBoost

✅ CatBoost

✅ RandomForest

✅ BaggingClassifier

 Also tested: Logistic Regression, Decision Tree, IsolationForest

 ## Final Ensemble Strategy ##
We selected our top two performing models (LightGBM and XGBoost) and took the mean of their predictions 


 ## Evaluation ##
 
Metric: log_loss

Validation: StratifiedKFold cross-validation

Tuning: RandomizedSearchCV
