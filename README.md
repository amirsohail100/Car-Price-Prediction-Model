# 🚗 Car Price Prediction Model

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-Scikit--Learn-orange.svg)](https://scikit-learn.org/)

## 📌 Overview

This repository contains a structured, end-to-end Machine Learning regression project designed to accurately estimate used car prices. By analyzing vehicle features like mileage, model year, and brand metrics, the pipeline processes and evaluates parametric and distance-based regression algorithms.

## 🎨 System Architecture Flow

The repository is designed following professional, modular data science practices:

[Dataset Ingestion] ➡️ [Feature Preprocessing & Scaling] ➡️ [Regression Modeling] ➡️ [Goodness-of-Fit Evaluation]

---

## 📊 Model Performance & Results

Since this is a continuous variable regression task, performance was evaluated using **Coefficient of Determination ($R^2$)** and **Adjusted $R^2$** scores to account for the explanatory features.

| Machine Learning Regressor       | $R^2$ Score (Variance Explained) | Adjusted $R^2$ Score |      Status       |
| :------------------------------- | :------------------------------: | :------------------: | :---------------: |
| 🏆 **K-Nearest Neighbors (KNN)** |            **92.62%**            |      _Dynamic_       | **Top Performer** |
| 📉 Linear Regression             |              73.66%              |        73.60%        |  Baseline Model   |

> 💡 **UI/UX & Developer Insight:** Linear assumptions underperformed due to complex, multi-dimensional correlations in automotive asset depreciation. The non-parametric structure of the **KNN Regressor** effortlessly mapped these local non-linearities, capturing **92.62%** of the target price variance.

---

## 🚀 Quick Start

### 1. Installation & Setup

Clone this specific repository setup directly to your machine:

```bash
git clone [https://github.com/amirsohail100/Car-Price-Prediction-Model.git](https://github.com/amirsohail100/Car-Price-Prediction-Model.git)
cd Car-Price-Prediction-Model
pip install -r requirements.txt
```

End-to-end Car Price Prediction regression pipeline built with Scikit-Learn. Evaluated parametric and distance-based architectures, where standard Linear Regression achieved a 73.66% R-squared baseline, and the optimized KNN Regressor delivered a top performance score of 92.62% in predicting car prices.
