Model Tuning:

1) Loan Delinquency Analysis (Loan_Delinquent_Analysis): <br>
A certain bank is interested in predicting the delinquency risk of its customers before loan approval. In order to do so,
a sample dataset of 10,000+ clients, containing their attributes such as gender, age, FICO score and home ownership status,
have been provided for ML-based modeling. Logistic regression has been adopted as the classification method. The further
boosting of the baseline model has been attempted using upsampling (oversampling), downsapling (undersampling) and 
regularization. <br>
Key tools: Logistic Regression, K-Fold Cross-Validation, Over/Undersampling, Regularization <br>
Libraries: scikit-learn, imblearn, scipy.stats, seaborn, matplotlib, numpy, pandas

1) Risk Analysis of Debtors for a German Bank (German_Credit_Analysis): <br>
A German financial services company seeks to utilize data-driven modeling, in order to separate its high-risk customers with
sizeable likelihood of default from the rest. Towards this goal, we're provided by a sample dataset of 1000 clients, 
comprising of features such as client's gender, size of checking and saving accounts, loan duration, home ownership status,
etc., and are tasked to develop an ML-based classification model, which meets the objective most efficiently and reliably.
A variety of classification models (Logistic Regression, Random Forest, XGBoost Classifier, etc.) along with model tuning
techniques (resampling, hyperparameter tuning, etc.), aimed at boosing the performance of models have been tried and, ultimately,
the best model is chosen based on recall score. <br>
Key tools: Classification, K-Fold Cross-Validation, Over/Undersampling, KNN-based Imputation, Hyperparameter Tuning,
Productionizing via Pipeline <br>
Libraries: scikit-learn, xgboost, imblearn, seaborn, matplotlib, numpy, pandas

3) Predictive Maintenance of Wind Farm Machineries (ReneWind): <br>
The encoded sensor data from processes involved in the production of wind energy has been collected by a wind farm 
equipment manufacturer called "ReneWind". The data consists of two sets: training and testing, respectively with 
20,000 and 5000 observations. The goal of the data science team is to build ML-based models capable of identifying
whether generators would fail or not. Towards this end, a wide variety of classification models (Decision Tree, 
Random Forest, XGBoost, etc.) have been adopted and their performances have been enhanced by leveraging up/downsampling
and model tuning.  
Key tools: Classification, K-Fold Cross-Validation, Over/Undersampling, KNN Imputer, Model Tuning, Python Pipelines <br>
Libraries: scikit-learn, xgboost, imblearn, seaborn, matplotlib, numpy, pandas

4) Insurance Classification Project (StateFarmProject):
The performances of two classification models, one linear (logistic regression) and one an intricate, tree-based model 
(XGBoost) have been compared on a large, imbalanced, dirty and masked dataset provided by an insurance company
(State Farm). It's been shown that the XGBoost classifier is able to render AUC scores (the main scoring metric to be 
evaluated accoridng to the problem statement) noticeably larger than those of the logistic regression model on unseen
datasets.
Key tools: Classification, K-Fold Cross-Validation, Undersampling, KNN Imputer, Model Tuning <br>
Libraries: scikit-learn, xgboost, imblearn, seaborn, matplotlib, numpy, pandas


