# Project Overview
Analysis of different machine learning algorithms in detecting fraud on basis roc-auc curve.<br>
## Details of dataset used for the project <br>
The data set was taken from the the kaggle . https://www.kaggle.com/mlg-ulb/creditcardfraud .<br>
The data set was highly imblanced with class distrubtion (99.83%  and 0.17%) <br>
![imbalnced](https://user-images.githubusercontent.com/56559327/144817025-aba7cf0b-0592-4eaa-9201-24b1958414ab.jpg). <br>
The dataset contained 1081 duplicates .<br>
The data was skewed
## Approach 
##### Data preprocessing
Out of 31 columns 28 were pca transformed leaving columns Time Amount and Class(Target).<br>
The time  column was dropped because the target class was evenly distributed on time leaving no pattern .<br>
Amount column was scaled.<br>
Duplicates were removed. <br>
Skewness was mitigated. <br>
##### Models on imblanced data 
Logistic regression. (Hyperparameter tuned) <br>
Decesion Tree. (Hyperparameter tuned) <br>
Xgboost. (Hyperparameter tuned) <br>
Random Forest. (Hyperparameter tuned) <br>
#### Balancing the Dataset and Models on balnced dataset
Undersampling.<br>
Oversampling.<br>
Smote.<br>


