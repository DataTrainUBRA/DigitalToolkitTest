---
title: Supervised Learning
parent: Machine Learning Basics
---

# Supervised Machine Learning

**Supervised machine learning** involves building a model that can map inputs to outputs based on example input-output pairs. It's one of the most prevalent and widely used branches of machine learning.

## Key Components

1. **Dataset**
   - **Inputs**: Features that describe the data.
   - **Outputs**: Labels or target values for each input.

2. **Algorithms**
   - Linear Regression: Predicts continuous values.
   - Decision Trees: Provides a tree-like model of decisions.
   - Random Forests: An ensemble of decision trees.

## Workflow

Here's a typical supervised learning workflow:

1. **Data Collection**: Gather and prepare data.
   1. Ensure data quality: Remove duplicates, handle missing values.
   2. Feature engineering: Create new useful features.

2. **Model Training**: Use algorithms to learn from the input-output pairs.

3. **Model Evaluation**: Assess the model performance using metrics like accuracy, precision, and recall.

- Example of evaluating accuracy:
  ```python
  from sklearn.metrics import accuracy_score
  
  accuracy_score(y_true, y_pred)
