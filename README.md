# mol_class
Machine Learning/AI through Emeritus/UCBerkeley

https://github.com/sramshey/mol_class/blob/main/molecule_classifier.ipynb

## Description

This project is an applied practical application of machine learning techniques
to a problem in molecular biology. The goal of the project is to create a model
that can accurately predict the class of a protein given only superficial data
related to the molecule such as residue count, molecular weight, crystal density,
pH, etc. The project uses several machine learning classification methodologies
and compares them in terms of accuracy and fitting time.

Step 1 - Data Review and Cleaning

The data was first reviewed and checked for consistency. Features appropriate for
classification modeling were selected, and unused features were removed. It was
determined that only a limited set of protein classifications had enough
representation in the data set for machine learning, so classifications without
adequate representation were removed.

Step 2 - Modeling

The project explored several models including LogisticRegression, DecisionTreeClassifier,
SVM, KNN, and RandomForestClassifier. The models were evaluated for initial accuracy, and
then a grid search was applied to optimize the hyperparameters.

Step 3 - Evaluation

The accuracy and fit time of each model was evaulated and compared, both before
and after optimization. The KNN and RandomForestClassifier had the best
performance, with KNN achieving 90% accuracy and the RandomForestClassifier achieving
around 95% accuracy on the test set.

Step 4 - Deployment

Findings were summarized for business presentation.

Author Contact Info Stefan Amshey sramshey@gmail.com
