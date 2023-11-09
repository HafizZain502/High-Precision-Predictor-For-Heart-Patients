# High-Precision-Predictor-For-Heart-Patients

## Overview
This project demonstrates the implementation of Classification Trees in Python using scikit-learn and Cost Complexity Pruning. The goal is to build a Classification Tree to predict whether or not a patient has heart disease based on continuous and categorical data from the UCI Machine Learning Repository.

## Steps Covered
### 1. Importing the Data
Load data from a file.

### 2. Missing Data
#### Part 1: Identifying Missing Data
Identify missing values in the dataset.
#### Part 2: Dealing with Missing Data
Remove rows with missing values.

### 3. Formatting the Data for Decision Trees
#### Part 1: Split Data into Dependent and Independent Variables
Split the data into features (X) and the target variable (y).
#### Part 2: One-Hot Encoding
Encode categorical variables using One-Hot Encoding.

### 4. Building a Preliminary Classification Tree
Use scikit-learn's DecisionTreeClassifier to build a preliminary tree.

### 5. Using Cost Complexity Pruning
Visualize alpha.
Perform cross-validation to find the best alpha.

### 6. Building, Drawing, Interpreting, and Evaluating the Final Classification Tree
Build the final Classification Tree.
Draw and interpret the tree.
Evaluate the tree using Confusion Matrices.

## Prerequisites
Python 3
Required Python modules:
pandas >= 0.25.1
numpy >= 1.17.2
scikit-learn >= 0.22.1
