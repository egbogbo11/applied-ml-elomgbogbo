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
# Lab 1
# Example California Housing Price Prediction
**Author:** Elom Gbogbo 

**Date:** March 13, 2025
  
**Objective:** Predict the median house price in California using available housing features.

## Introduction
This project uses the California housing dataset to predict house prices based on features such as median income, average number of rooms, and house age. We'll clean the data, train a linear regression model, and explore ways to improve performance.

https://github.com/egbogbo11/applied-ml-elomgbogbo/blob/main/lab01/ml01.ipynb 

## Project Outline
### Imports
- Import the external Python libraries used (e.g., pandas, numpy, matplotlib, seaborn, sklearn, etc.) 
  
### Section 1. Load and Explore the Data
- 1.1 Load the dataset and display the first 10 rows.
- 1.2 Check for missing values and display summary statistics.

Analysis: What do you notice about the dataset? Are there any data issues?

### Section 2. Visualize Feature Distributions
- 2.1 Create histograms, boxplots, and scatterplots.
- 2.2 Identify patterns or anomalies in feature distributions.

Analysis: What patterns or anomalies do you see? Do any features stand out?

### Section 3. Feature Selection and Justification
- 3.1 Choose two input features for predicting the target.
- 3.2 Justify your selection with reasoning.

Analysis: Why did you choose these features? How might they impact predictions?

### Section 4. Train a Linear Regression Model
- 4.1 Define X (features) and y (target).
- 4.2 Train a Linear Regression model using Scikit-Learn.
- 4.3 Report R^2, MAE, RMSE.

Analysis: How well did the model perform? Any surprises in the results?





