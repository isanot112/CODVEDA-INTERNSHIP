# 📊 Research Findings & Analytical Insights: Iris Dataset Analysis

## 🎯 Executive Summary
This research document details the exploratory data analysis (EDA), statistical evaluation, and data cleaning pipeline executed on the **Iris Dataset** using Python and Google Colab. The primary objective is to evaluate morphological differences across iris species (`setosa`, `versicolor`, `virginica`) to establish reliable classification benchmarks.

---

## 📈 Key Findings & Statistical Insights

### 1. Central Tendency & Dispersion
* **Sepal Length**: Ranges from $4.30	ext{ cm}$ to $7.90	ext{ cm}$, with a mean of $5.84	ext{ cm}$ and a standard deviation of $0.83	ext{ cm}$.
* **Sepal Width**: Concentrated around a mean of $3.06	ext{ cm}$ with a median of $3.00	ext{ cm}$.
* **Petal Length**: Demonstrates the widest variability, ranging from $1.00	ext{ cm}$ to $6.90	ext{ cm}$, serving as a primary differentiator between species.
* **Petal Width**: Averages $1.20	ext{ cm}$ with a strong positive skew for *virginica* specimens.

### 2. Feature Correlation Analysis
* **Petal Dimensions Correlation**: There is an exceptionally strong positive linear correlation between **petal length** and **petal width** ($r \approx 0.96$). As petal length increases, petal width increases proportionally across all species.
* **Sepal vs. Petal Relationship**: Sepal length also correlates strongly with petal length ($r \approx 0.87$), whereas sepal width exhibits a slight negative correlation with petal dimensions.

### 3. Species Classification Separability
* ***Iris setosa*** is linearly separable from the other two species based entirely on its significantly smaller petal length and width.
* ***Iris versicolor*** and ***Iris virginica*** exhibit slight overlap in sepal dimensions but remain distinctly separable through comprehensive multi-feature cluster analysis.

---

## 🖼️ Visualizations & Graphical Evidence

### * Average Petal Length by Species
The bar plot below illustrates the distinct progression in average petal lengths across the three flower species:
* **Setosa**: $\sim 1.48	ext{ cm}$
* **Versicolor**: $\sim 4.26	ext{ cm}$
* **Virginica**: $\sim 5.55	ext{ cm}$

---

## 🔬 Methodology & Pipeline
1. **Data Cleaning**: Handled missing values via statistical imputation and eliminated duplicate entries.
2. **Standardization**: Standardized headers and normalized species classification labels.
3. **Statistical Modeling**: Generated descriptive statistics, correlation matrices, and distribution metrics.

---
*Report Compiled by Isaac Salifu Nortey Tetteh | BSc. Mathematics and Statistics, University of Cape Coast*
