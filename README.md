# Pumpkin Seed Classification using LDA and MLP

## Overview
This project analyzes a pumpkin seed dataset to classify two types of pumpkin seeds: **Çerçevelik** and **Ürgüp Sivrisi**. The dataset includes features related to pumpkin seed characteristics, such as area, perimeter, major and minor axis lengths, and various shape descriptors.

## Dataset
- The dataset contains **[number of samples] samples** and **[number of features] features**.
- The target variable 'Class' represents the type of pumpkin seed.

## Exploratory Data Analysis (EDA)
- Conducted univariate and bivariate analyses to derive key insights about data distributions and relationships between variables.
- Notable observations include strong positive correlations between attributes like area, perimeter, and convex area.

## Model Performance Comparison
Three classification models were evaluated:
1. **Linear Discriminant Analysis (LDA)**: Accuracy of 0.868, with balanced precision, recall, and F1-score.
2. **Logistic Regression**: Accuracy of 0.856, showing similar performance metrics to LDA.
3. **Multilayer Perceptron (MLP)**: Accuracy of 0.864, outperforming LDA and Logistic Regression in terms of accuracy but with comparable precision, recall, and F1-score.

## Recommendations
- **Model Selection**: Choose based on computational complexity and interpretability needs.
- **Feature Importance**: Explore techniques like feature importance plots to identify key predictors.
- **Model Interpretability**: Consider LDA for its interpretability despite MLP's higher accuracy.
- **Model Refinement**: Engage in continual evaluation, hyperparameter tuning, and feature engineering.
- **Data Augmentation**: Collect more data to enhance model performance.

By implementing these recommendations, the project aims to enhance the classification accuracy and reliability for identifying pumpkin seed types, contributing to agricultural research and practices.

---
