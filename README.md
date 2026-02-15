# FitStats-Analytics

Statistical analysis and predictive modeling of gym member fitness data.

## Overview

Comprehensive exploratory and statistical analysis of 973 gym members covering:
- Physical attributes (age, weight, height, BMI, body fat)
- Exercise routines (type, duration, frequency, intensity)
- Performance metrics (calories burned, heart rate)

## Analysis Performed

**Exploratory Analysis**
- Descriptive statistics and correlation matrices
- Principal Component Analysis (PCA) & Multiple Correspondence Analysis (MCA)
- Pattern identification via clustering (3 distinct member groups)

**Statistical Testing**
- Hypothesis tests (Shapiro-Wilk, Kolmogorov-Smirnov, Chi-squared)
- Normality and independence checks
- Gender & sport type dependency analysis

**Clustering**
- Hierarchical Agglomerative Clustering (HAC) with Ward linkage
- K-means clustering (K=3 optimal)
- Gaussian Mixture Models (Mclust)
- Cluster comparison (Adjusted Rand Index)

**Predictive Modeling**
- Multiple regression for calories burned (R² = 0.97)
- Two-way ANOVA with interactions
- ANCOVA with model selection (AIC/BIC)
- Logistic regression for experience level prediction

## Key Findings

- **Calories Model**: Duration & heart rate are primary drivers (R² = 0.99 with interactions)
- **Experience Level**: Session duration is strongest predictor (p < 0.001)
- **Clustering**: Members separate into athletic high-performers + 2 morphology-based groups
- **Gender Effect**: No significant difference in training habits, only physical attributes

## Files

- `StatsCode.qmd` - Quarto source code (R + Markdown)
- `Rapport-Projet.pdf` - Final report (25 pages max)
- Data: 973 gym members × 13 variables

## Methods

- **R Packages**: ggplot2, factoextra, mclust, stats, lme4
- **Techniques**: PCA, MCA, HAC, K-means, Mclust, linear/logistic regression, AIC/BIC selection

## Authors

Boulaalam El-Mehdi, Ajerame Ilias, Grande Revuelta Ana

**Course**: Data Analysis & Statistical Modeling (ModIA UF)  
**Institution**: INSA Toulouse  
**Date**: January 2026

---

**Note**: Final report limited to 25 pages. Code available in .qmd file.