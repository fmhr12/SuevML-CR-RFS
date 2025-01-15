# Survival Analysis with Random Forests and Repeated Cross-Validation

## Overview

This repository contains R scripts designed for performing advanced survival analysis using Random Forest Survival (RFS) models considering the competing risk. The workflow incorporates repeated 5-fold cross-validation to ensure robust model evaluation. Key evaluation metrics such as time-dependent Area Under the Curve (AUC), Brier Score, Integrated Brier Score (IBS), and Concordance Index (C-index) are computed. Additionally, the repository includes comprehensive visualization tools for assessing model performance and calibration.

## Features

- **Data Loading and Preparation**: Efficiently loads and preprocesses survival data from Excel files.
- **Repeated Cross-Validation**: Implements a 5×5 cross-validation strategy to assess model stability and performance.
- **Model Training**: Utilizes Random Forest Survival models with optimal hyperparameters.
- **Comprehensive Evaluation**: Calculates AUC, Brier Score, IBS, and C-index at multiple time horizons.
- **Visualization**: Generates time-dependent AUC and Brier Score plots with 95% confidence intervals.
- **Calibration Analysis**: Provides calibration plots at specific time points to evaluate model reliability.
- **Result Summarization**: Aggregates and summarizes evaluation metrics across all cross-validation splits.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/survival-analysis-rfs.git
   cd survival-analysis-rfs
   ```
2. **Install Required R Packages**
Ensure you have R installed on your system. Then, install the necessary packages:

  ```bash
  install.packages(c(
    "survival",
    "readxl",
    "dplyr",
    "riskRegression",
    "ggplot2",
    "caret",
    "pec",
    "randomForestSRC",
    "tidyr"
  ))
```
![License](https://img.shields.io/badge/license-MIT-blue.svg)

**Contact**
        
For any questions or inquiries, please contact your.email@example.com.

