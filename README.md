BITS ML Assignment 2

a.Problem statement
---------------------

The objective of this project is to build and compare multiple machine learning classification models for predicting whether an individual's annual income exceeds $50,000 based on demographic and employment-related attributes.

The project involves data preprocessing, handling missing values, encoding categorical variables, scaling features, and evaluating different machine learning algorithms using multiple performance metrics.

The following classification algorithms are implemented:

Logistic Regression
Decision Tree Classifier
K-Nearest Neighbor (KNN) Classifier
Naive Bayes Classifier
Random Forest Classifier (Ensemble Method)

b.Dataset description
-----------------------

Dataset Name: Adult Census Income Dataset
Source: [https://archive.ics.uci.edu/ml/datasets/adult](https://www.kaggle.com/datasets/uciml/adult-census-income)
Instances: 48,842
Features: 14
Target Variable: Income
Classes: <=50K
50k

Missing Values: Present in workclass, occupation and native-country.

c.Github Repository Link
-------------------------
[2026ct05115-prog/2026CT05115: ML-ASSIGNMENT-2](https://github.com/2026ct05115-prog/2026CT05115)

d. Models Used
-----------------

1. Logistic Regression
Used as a baseline classification algorithm.

2. Decision Tree Classifier
Used to capture nonlinear relationships between variables.

3. K-Nearest Neighbors (KNN)
Used as an instance-based learning algorithm.

4. Naive Bayes
Probabilistic classifier based on Bayes' theorem.

5. Random Forest (Ensemble)
An ensemble learning algorithm combining multiple decision trees.

## Model Comparison Table

| ML Model Name | Accuracy | AUC | Precision | Recall | F1 | MCC |
|---------------|----------|------|-----------|--------|------|------|
| Logistic Regression | 0.8502 | 0.9004 | 0.7344 | 0.5925 | 0.6558 | 0.5668 |
| Decision Tree | 0.8099 | 0.7407 | 0.6052 | 0.6071 | 0.6062 | 0.4809 |
| KNN | 0.8274 | 0.8510 | 0.6618 | 0.5804 | 0.6184 | 0.5094 |
| Naive Bayes | 0.5244 | 0.7218 | 0.3305 | 0.9496 | 0.4904 | 0.3142 |
| Random Forest (Ensemble) | 0.8488 | 0.8956 | 0.7802 | 0.5185 | 0.6230 | 0.5506 |








