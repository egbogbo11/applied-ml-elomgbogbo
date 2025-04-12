# Lab 5 Project (Titanic)

## Objective
To predict red wine quality levels using ensemble machine learning models based on physicochemical attributes.

## Models Created
Random Forest and AdaBoost ensemble models was used in the project.

## Outline
### Section 1. Load and Inspect the Data
- 1.1 Load the dataset.

### Section 2. Data Exploration and Preparation
- Includes cleaning, feature engineering, encoding, splitting, helper functions

### Section 3. Feature Selection and Justification
- Choose three input features for predicting the target. Justify your selection with reasoning.
- Define X (features) and y (target).

### Section 4. Split the Data into Train and Test

### Section 5. Evaluate Model Performance (Choose 2)
1. Random Forest (100), A strong baseline model using 100 decision trees.
2. Random Forest (200, max_depth=10), Adds more trees, but limits tree depth to reduce overfitting.
3. AdaBoost (100), Boosting method that focuses on correcting previous errors.
4. AdaBoost (200, lr=0.5), More iterations and slower learning for better generalization.
5. Gradient Boosting (100), Boosting approach using gradient descent.
6. Voting (DT + SVM + NN), Combines diverse models by averaging their predictions.
7. Voting (RF + LR + KNN), Another mix of different model types.
8. Bagging (DT, 100), Builds many trees in parallel on different samples.
9. MLP Classifier, A basic neural network with one hidden layer.