# Urban Flood Risk Prediction Using Machine Learning

## Overview

This project investigates urban flood risk prediction using environmental and drainage-related variables. Several machine learning classification algorithms were evaluated, including Decision Tree, KNN, Logistic Regression, and Random Forest.

## Dataset

Urban Flood Risk Data: Global City Analysis 2025

Source:
https://www.kaggle.com/datasets/pratyushpuri/urban-flood-risk-data-global-city-analysis-2025

## Installation

```bash
pip install -r requirements.txt

## Objectives

- Predict urban flood risk
- Compare machine learning algorithms
- Identify the most influential flood-risk factors
- Evaluate the role of elevation, rainfall intensity, and drainage characteristics

## Models

- Decision Tree
- K-Nearest Neighbors
- Logistic Regression
- Random Forest

  ## Results

| Model | Accuracy | F1 Score |
|---------|---------:|---------:|
| Random Forest | 99.33% | 98.98% |
| Decision Tree | 98.99% | 98.47% |
| KNN | 86.17% | 78.19% |
| Logistic Regression | 78.25% | 68.61% |

## Key Findings

- Random Forest achieved the highest performance.
- Elevation was identified as the dominant predictor.
- Elevation was more influential than rainfall intensity.
- Removing elevation reduced F1-score from 98.98% to 57.44%.
- Three variables explained almost all predictive power:
  - Elevation
  - Historical Rainfall Intensity
  - Drainage Density


