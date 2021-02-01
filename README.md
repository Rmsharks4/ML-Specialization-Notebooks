# ML-Specialization-Notebooks
This repository contains Jupyter Notebooks built whilst taking some introductory courses of DataCamp's Machine Learning Specialization.  
> Note: These notebooks might not follow the exact order or content of the exercises, as the purpose of creating these was to do complete / extended analysis on the practice exercises in the specialization, and try to improve knowledge beyond the sample Q&As. These are also about 1.5 years old, so if the courses have updated now, then you might not find them as useful today.

### 0. Data Manipulation with Pandas
An Introduction to the Pandas Python API for cleaning data (imputation, analysis, reporting, etc.)


### 1. Introduction to PySpark  
Apache PySpark Basics (Context, DataFrames and SparkML) with Flights Dataset (and reference airports and planes):
|year|month|day|dep_time|dep_delay|arr_time|arr_delay|carrier|tailnum|flight|origin|dest|air_time|distance|hour|minute|
|----|-----|---|--------|---------|--------|---------|-------|-------|------|------|----|--------|--------|----|------|
|2014|   12|  8|     658|       -7|     935|       -5|     VX| N846VA|  1780|   SEA| LAX|     132|     954|   6|    58|
|2014|    1| 22|    1040|        5|    1505|        5|     AS| N559AS|   851|   SEA| HNL|     360|    2677|  10|    40|
|2014|    3|  9|    1443|       -2|    1652|        2|     VX| N847VA|   755|   SEA| SFO|     111|     679|  14|    43|
|2014|    4|  9|    1705|       45|    1839|       34|     WN| N360SW|   344|   PDX| SJC|      83|     569|  17|     5|
|2014|    3|  9|     754|       -1|    1015|        1|     AS| N612AS|   522|   SEA| BUR|     127|     937|   7|    54|


### 2. Supervised Learning with Scikit-Learn
Scikit-Learn Basics for the following models:
- KNeighborsClassifier
- LinearRegression
- LogisticRegression
- DecisionTreeClassifier
- ElasticNet  

alongwith Pipeline Components like:
- Hyper-Parameter Tuning and Cross Validation: RandomizedSearchCV, GridSearchCV
- Data PreProcessors: Imputer, StandardScaler
- Loss and Metrics: LogLoss, MSE, F1-Score, etc.


### 3. Unsupervised Learning in Python
Scikit-Learn Models for Unsupervised Learning:
- K-Means Clustering
- Heirarchial Clustering with Linkage and Dendograms
- tSNE Scatter Plots
- Pearson's Correlation and PCA
- TruncatedSVD and Non-Negative Matrix Factorization (NMF)


### 4. Linear Classifiers in Python
Based on the Large Movie Reviews Dataset (http://ai.stanford.edu/~amaas/data/sentiment/), it shows a comparison between the Scikit-Learn's Linear Classifiers: KNeighborsClassifier, LogisticRegression, Support Vector Machine (svm.SVC and LinearSVC) and SGDClassifier, as well as an exploration into Regularization Types, Strengths and Losses.


### 5. Machine Learning with Tree-Based Models in Python
Scikit-Learn Tree-Based Model Implementations (Intro):
- Voting Classifier with different base-estimators
- Bagging Classifier with Decision Trees
- Random Forest Regressor (RF Algorithm)
- AdaBoost Classifier and Gradient Boosting Regressor
- Stochastic Gradient Boosting Classifier


### 6. Extreme Gradient Boosting in Python
An introduction to XGB Dataset Format (DMatrix), XGBClassifier and XGBRegressor, with detail into Hyper-Parameter Tuning and Cross Validation for:
- No. of Estimators
- Max. Depth
- Learning Rate
- Column Sample by Tree (Max. Features)


### 7. Statistical Thinking in Python
A Practice run of Statistical Analysis Techniques in Python using:
- Histograms and Binning with SwarmPlots
- Empirical Distribution Functions and Cummulative Distribution Functions
- Probability Mass Functions and Probability Distribution Functions
- Quantiles and Percentiles with BoxPlots
- Variance, Covariance and Correlations
- Probability Theory and Bernoulli Trials
- Binomial and Poisson Distributions


All Source Code Copyrights to DataCamp and its contributors. All Dataset Copyrights to the official citings inside the Jupyter Notebooks.
