# HR-Attrition

Problem Statement_1: For the given dataset, predict 'Monthly Rate' for the employees.
Problem Statement_2: For the given dataset, predict 'Attrition' status for the employees.
Problem Statement_3: For the given dataset, form clusters by taking into consideration the relatable features.


Steps involved into developing this model

1. Remove columns with unique values.
2. Missing data treatment.
3. Data Visualization.
4. Pre-processing on data such as One Hot Encoding for categorical columns and Standardization for continuous columns.
5. Diving the dataset into training and testing sets.
6. Check correlation with other columns in the dataset and choose best features for the model.


Models used for predictions:

for predicting Monthly Rate:
1. Linear Regression 
2. Lasso 
3. Ridge
4. DecisionTreeRegressor
5. RandomForestRegressor
6. AdaBoostRegressor
7. KNeighborsRegressor

for predicting Attrition status:
1. LogisticRegression
2. DecisionTreeClassifier
3. RandomForestClassifier
4. AdaBoostClassifier
5. GaussianNB
6. keras Tuner 

for Custering:
KMeans Clustering
