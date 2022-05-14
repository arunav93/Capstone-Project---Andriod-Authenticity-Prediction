# Capstone-Project---Andriod-Authenticity-Prediction
#  Problem Statement
This dataset consists of apps needed permissions during installation and run-time. We collect apps from three different sources google play, third-party apps and malware dataset. This file contains more than 30,000 Android apps. features extracted at the time of installation and execution. One file contains the name of the features and others contain .apk file corresponding to it extracted permissions with respective package. Apps are collected from Google's play store, hiapk, app china, Android, mumayi , gfan slideme, and pandaapp. These .apk files collected from the last three years continuously and contain 81 distinct malware families. But, Here you are only supposed to predict whether the app is benign(0) or malware(1).
# Part of dataset features
* Class :- Whether the app is Benign(0) or Malware(1) :-
* App :- Name of the App
* Package :- OBB/Data package installed in root folder
* Category :- App Category (eg. Entertainment, Adventure, puzzle, Action, Antivirus, etc.)
* Description :- App Description
* Rating :- Rating out of 5
* Number of ratings :- No. of Ratings given by users
* Price :- Price of the App
* Related apps :- Apps related to installed App
* Dangerous (D) permissions count :- No. of Dangerous Permissions allowed by user
* Safe (S) permissions count :- No. of Safe Permissions allowed by user
* Default : Access DRM content. (S) :- 0 : No , 1 : Yes
* Phone calls : modify phone state (S) :- 0 : No , 1 : Yes
#  Steps involved
Installing libraries and gathering the dataset
i) Pre-processing the dataset: - Checking for Missing values, Duplicate values etc.
ii) Exploratory Data Analysis: - Analysing the dependent variable, categorical and numerical variables individually.
iii) Feature Engineering: - Creation of new features according to our need, dropping of unnecessary data points or features by checking correlation, VIF etc., handling of outliers, One–Hot Encoding and normalization of features.
iv) Fitting of Machine Learning models with training dataset and evaluating with testing dataset: - like Linear regression, Decision Tress, Random Forest, Gradient Boosting
v) Hypertuning and Explaining the best model with LIME and ELI5.
# Observations
Logistic Regression has the best F1 Score of almost 91% for both train and test dataset. 
