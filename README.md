# mol_class

Author: Stefan Amshey sramshey@gmail.com

## Executive Summary and Description

This project is an applied practical application of machine learning techniques
to a problem in molecular biology. The goal of the project is to create a model
that can accurately predict the class of a protein given only superficial data
related to the molecule such as residue count, molecular weight, crystal density,
pH, etc. The project uses several machine learning classification methodologies
and compares them in terms of accuracy and fitting time.

This project was undertaken as part of the Machine Learning/AI course offered
through Emeritus/UCBerkeley

## Rationale

Novel genomes are being sequenced faster and more efficiently than ever before,
resulting in a large amount of uncharacterized gene sequencess. This creates an
opportunity for researchers, drug companies, other bioprospectors to make use of it.

Characterization of proteins, by contrast, is a rate-limiting step, and often
involves time-consuming and computationally expensive operations like sequence matching
across large datasets in order to make inferences about the possible function of a
given  protein. Therefore, the ability to characterize proteins using superficial
characteristics alone could potentially accelerate research and drug discovery.

## Research question

Is it possible to use machine learning methods to perform accurate classification
of proteins based on superficial characteristics alone, and without using sequence
matching?

## Data Sources

The data used for this project was sourced originally from Protein Data Bank (PDB).

## Methodology

### Step 1 - Data Review and Cleaning

The data was first reviewed and checked for consistency. Features appropriate for
classification modeling were selected, and unused features were removed. It was
determined that only a limited set of protein classifications had enough
representation in the data set for machine learning, so classifications without
adequate representation were removed.

### Step 2 - Modeling

The project explored several models including LogisticRegression, DecisionTreeClassifier,
SVM, KNN, and RandomForestClassifier. The models were evaluated for initial accuracy, and
then a grid search was applied to optimize the hyperparameters.

### Step 3 - Evaluation

The accuracy and fit time of each model was evaulated and compared, both before
and after optimization. 

Additional evaluation is pending.

## Results

The KNN and RandomForestClassifier had the best
performance, with KNN achieving 90% accuracy and the RandomForestClassifier achieving
around 95% accuracy on the test set.

## Next Steps

## Outline of Project

The notebook showing the process in code can be found here:

https://github.com/sramshey/mol_class/blob/main/molecule_classifier.ipynb

## Contact and Further Information

Author Contact Info Stefan Amshey sramshey@gmail.com


