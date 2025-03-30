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
# Lab 3
# Example Titanic Survival Prediction
**Author:** Elom Gbogbo 

**Date:** March 28, 2025
  
**Objective:** Predict passenger survival on the Titanic by building a classification model to evaulate different models using key features such as class, gender, and age.

## Introduction

This project analyzes the Titanic dataset using Seaborn to predict passenger survival based on features. We’ll clean the data, train a classification model, evaluate different models and explore techniques to improve its performance.

https://github.com/egbogbo11/applied-ml-elomgbogbo/blob/main/lab02/ml03_elomgbogbo.ipynb 

## Project Outline
### Imports
- Import the external Python libraries used (e.g., pandas, numpy, matplotlib, seaborn, sklearn, etc.) 
  
### Section 1. Load and Inspect the Data
- 1.1 Load the dataset.

### Section 2. Data Exploration and Preparation
- 2.1 Handle Missing Values and Clean Data
- 2.2 Feature engineering 


### Section 3. Feature Selection and Justification
- 3.1 Choose three input features for predicting the target. Justify your selection with reasoning.
- 3.2 Define X (features) and y (target).


### Section 4. Train a Classification Model
- 4.1 Split the data into training and test sets using StratifiedShuffleSplit for each feature case. 
- 4.2 Create and Train Model - Decision Tree
- 4.3 Predict and Evaluate Model Performance
- 4.4 Report Confusion Matrix (as a heatmap)
- 4.5 Report Decision Tree Plot

### Section 5. Compare Alternative Models (SVC, NN)
- 5.1 Train and Evaluate Model (SVC)
- 5.2 Train and Evaluate Model (NN MLP)
- 