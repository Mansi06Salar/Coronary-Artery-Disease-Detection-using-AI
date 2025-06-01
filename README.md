# Coronary-Artery-Disease-Detection-using-AI


1. Dataset: Z-Alizadeh Sani dataset (publicly available in the UCI Machine Learning
repository)
Description: 303 samples and 55 features
· Numerical (34 columns): Age, BMI, BP, PR, various blood test values, etc.

· Categorical (21 columns): Sex, Obesity, CHF, Dyspnea, etc.
· Target Variable (Cath): Indicates whether a patient has CAD (Cad) or is normal
(Normal).
● Kaggle url for dataset:
https://www.kaggle.com/datasets/saeedeheydarian/classification-of-coronary-a
rtery-disease


2. Preprocessing:
1. Renamed column Cath to CAD and Length to Height
2. Used Label encoding on categorical features
3. Dropped column ‘Exertional CP’ (it contained only N as a value for all instances)
4. No missing values
5. Used StandardScaler on Numeric features
6. URL :
https://drive.google.com/file/d/1pkaWrgfV6iP12LdrL472nypYy7IP1u5D/view?usp=s
haring



Ensemble (Base models: AdaBoost and CatBoost, Meta-model:
RandomForest)
Google colab:
https://colab.research.google.com/drive/1x9N-hAMMLObkA1ZyCvPVro_OuZ9NMBQm?usp=
sharing



Feature Engineering:
In the feature engineering process for the coronary artery disease (CAD) detection project,
the dataset initially contained 54 features (columns), with 303 samples (rows). The objective
was to enhance the model’s performance by selecting the most relevant features.
Key Steps:
1. Correlation Analysis: The top 30 features most correlated with the target variable
(CAD) were identified.

2. Random Forest Feature Importance: The Random Forest model was applied to
evaluate the importance of features, further narrowing down the selection.
3. Principal Component Analysis (PCA): PCA was used to reduce dimensionality
while retaining 95% of the variance, optimizing the feature set.
Results:
After feature engineering, the dataset was reduced to 31 features, which significantly refined
the data while preserving the key information necessary for prediction.
Updated dataset:
https://drive.google.com/file/d/1OoqNRFQgH_1HJ80990y_n5yblq3FD_AL/view?usp=s
haring




