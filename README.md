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
Libraries: scikit-learn, imblearn, seaborn, matplotlib, numpy, pandas
