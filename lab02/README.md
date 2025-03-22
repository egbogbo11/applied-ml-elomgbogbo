# applied-ml-elomgbogbo

## Make repository in Github and clone to local workspace
```bash
git clone https://github.com/egbogbo11/applied-ml-elomgbogbo
```

## Create .gitignore file
Ensure the following entries are added to your .gitignore file to exclude unnecessary files from being committed:

```bash
# Python virtual environment folder
.venv/

# Visual Studio Code settings and workspace folder - Ignore entire .vscode folder except settings.json
.vscode/*
!.vscode/settings.json

# Compiled Python files
__pycache__/

# macOS system files
.DS_Store

# Jupyter Notebook checkpoint files
.ipynb_checkpoints
```

## Create and activate virtual environment

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment:

```bash
.\.venv\Scripts\activate
```
## Create requirement.txt and download imports
Add the following libraries to your requirements.txt file:

```bash
jupyterlab
numpy
pandas
pyarrow
matplotlib
seaborn
scklit-learn
```

Install into your active project virtual environment with this command:

```bash
py -m pip install -r requirements.txt
```
## Stage and Push Files to GitHub

Use the following Git commands to stage and commit changes:

```bash
git add .
git commit -m "commit: message"
git push origin main
```
# Lab 2
#
**Author:** Elom Gbogbo 

**Date:** March 21, 2025
  
**Objective:** Predict passenger survival on the Titanic by building a classification model using key features such as class, gender, and age.

## Introduction

This project analyzes the Titanic dataset using Seaborn to predict passenger survival based on features like class, gender, and age. We’ll clean the data, train a classification model, and explore techniques to improve its performance.

https://github.com/egbogbo11/applied-ml-elomgbogbo/blob/main/lab02/ml02_elomgbogbo.ipynb 

## Project Outline
### Imports
- Import the external Python libraries used (e.g., pandas, numpy, matplotlib, seaborn, sklearn, etc.) 
  
### Section 1. Load and Explore the Data
- 1.1 Load the dataset and display the first 10 rows.
- 1.2 Check for missing values and display summary statistics.



### Section 2. Visualize Feature Distributions
- 2.1 Create a histogram, countplot, and scatter plot.
- 2.2 Identify patterns or anomalies in feature distributions.



### Section 3. Feature Selection and Justification
- 3.1 Choose two input features for predicting the target. Justify your selection with reasoning.
- 3.2 Define X (features) and y (target).


### Section 4. Splitting
- 4.1 Split the data into training and test sets using train_test_split first and StratifiedShuffleSplit second. Compare.








