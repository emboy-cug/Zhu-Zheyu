# Data Mining Homework 2 - Spring 2025

This repository contains the solutions to the Data Mining Homework 2 for CS 422, Spring 2025. The problems focus on using Python and the `sklearn` library to work with decision trees, evaluate performance metrics, and explore PCA for dimensionality reduction.

## Problem 1: Decision Trees on the Iris Dataset

- **Goal:** Induce binary decision trees using the Iris dataset from `sklearn`, experiment with different tree depths (1 to 5), and evaluate the performance based on Recall, Precision, and F1 score.
- **Libraries Used:** `sklearn`, `pandas`, `matplotlib`
- **Metrics:**
  - Best depth for Recall: `max_depth = 5`
  - Lowest Precision: `max_depth = 1`
  - Best F1 Score: `max_depth = 2`

## Problem 2: Decision Trees on Breast Cancer Dataset

- **Goal:** Use the Breast Cancer Wisconsin dataset and train a decision tree with a max depth of 2. Compute Entropy, Gini, and Misclassification Error, then calculate the Information Gain for the first split.
- **Libraries Used:** `sklearn`, `pandas`
- **Output:** Information Gain and First Split Feature analysis

## Problem 3: PCA on the Breast Cancer Dataset

- **Goal:** Apply PCA dimensionality reduction to the continuous version of the Breast Cancer dataset, and compare model performance (F1, Precision, Recall) with and without PCA.
- **Libraries Used:** `sklearn`, `pandas`
- **Results:** F1 scores, Precision, and Recall comparisons for original vs. PCA-based models.

## Installation

To install the necessary libraries, run:

```bash
pip install -r requirements.txt
