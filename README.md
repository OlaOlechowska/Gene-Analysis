# Gene-Analysis
Statistical analysis of gene expression

## CD36 Protein Expression Analysis

**Author:** Aleksandra Olechowska  
**Date:** May 2025  

---

## Project Overview
This project explores and models the surface protein **CD36** expression levels using statistical analysis and basic machine learning methods in **R**.  
The workflow includes data exploration, statistical testing, and predictive modeling.

---

## Methods and Calculations

### 1. Data Exploration
- Imported training and test datasets (`X_train`, `X_test`, `y_train`).
- Checked data completeness and basic descriptive statistics.
- Created histograms and a correlation heatmap for the most correlated features.

### 2. Statistical Tests
- Verified normality using the Kolmogorov–Smirnov test.
- Fitted a theoretical distribution (exponential) and evaluated its fit.
- Compared distributions between training and test sets using the Wilcoxon test.
- Visualizations included Q-Q plots, histograms, and density plots.

### 3. Predictive Modeling
- Implemented **ElasticNet regression** and **Random Forest** models.
- Used **cross-validation** for hyperparameter tuning and model comparison.
- Created boxplots and violin plots to visualize MSE distributions.

---

## Libraries Used

```r
library(dplyr)
library(ggplot2)
library(stats4)
library(MASS)
library(glmnet)
library(randomForest)
library(gplots)

