<h1 align="center">Capstone-Project---Andriod-Authenticity-Prediction</h1>
<p align="center">
  <img width="460" height="300" src="https://cdn.arstechnica.net/wp-content/uploads/2018/01/android-malware.jpg">   
</p>

#  Problem Statement
The dataset given consists of apps needed permissions during installation and run-time. Different apps are collected from  different sources like Google's play store, hiapk, app china, Android, mumayi , gfan slideme, and pandaapp. The dataset contains more than 30,000 Android apps, its features and numerous permissions required at the time of installation and execution. Our objective is to predict whether the app is benign(0) or malware(1).
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
* i) Installing libraries and gathering the dataset
* ii) Pre-processing the dataset: - Checking for Missing values, Duplicate values etc.
* iii) Exploratory Data Analysis: - Analysing the dependent variable, categorical and numerical variables individually.
* iv) Feature Engineering: - Creation of new features according to our need, dropping of unnecessary data points or features by checking correlation, VIF etc., handling of outliers, One–Hot Encoding and normalization of features.
* v) Fitting of Machine Learning models with training dataset and evaluating with testing dataset: - like Logistic regression, Decision Tress, Random Forest, Gradient Boosting, XGBoost, KNN, Naive Bayes.
* vi) Hypertuning and Explaining the best model with LIME and ELI5.
# Observations
Logistic Regression is the best performed model with F1 Score of almost 91% for both train and test dataset. 
