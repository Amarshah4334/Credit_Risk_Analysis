# Credit_Risk_Analysis
Use machine learning model to predict credit risk
The lead data scientist, Jill, has asked you to create the same development environment that she is using. This step will help you run the code smoothly without conflicts.

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Overview of the analysis: 
Explain the purpose of this analysis.

We will use Python and Jupyter notebooks with Machine Learning to predict credit risk.

1. Deliverable 1: Use Resampling Models to Predict Credit Risk
2. Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
3. Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
4. Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)

Oversampling using the RandomOverSampler and SMOTE.
Undersamplling ClusterCentroids.
Combine over and undersampling using the SMOTEENN.
Compare the two machine learning models and reduce bias, 
    1. BalancedRandomForestClassifier and 
    2. EasyEnsembleClassifier.
Finally evaluate the performance of these models to make a recommendation whether they are effective for predicting credit risk.

Resources
Data: LoanStats_2019Q1.csv
Software: Python, Anaconda Navigator, Jupyter Notebook, Machine Learning environment using(numpy, scipy, scikit_learn)

# Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

# Oversampling
1. Naive Random Oversampling
2. SMOTE Oversampling
# Undersampling
# Combination (Over and Under) Sampling
# Balanced Random Forest Classifier
# Easy Ensemble AdaBoost Classifier




# Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.