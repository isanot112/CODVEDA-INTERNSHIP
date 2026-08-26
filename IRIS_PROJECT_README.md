# 🌸 Iris Dataset Exploratory Data Analysis & Machine Learning Pipeline

A comprehensive end-to-end data analysis project exploring the classic **Iris Dataset** using **Python, Pandas, NumPy, Matplotlib, and Seaborn** inside **Google Colab**. 

This project covers foundational data science workflows: Data Cleaning, Exploratory Data Analysis (EDA), Statistical Summaries, and Custom Data Visualizations.

---

## 📁 Repository Structure
```text
├── 1) iris.csv                 # Raw & cleaned dataset
├── iris_analysis.ipynb         # Complete Google Colab notebook
├── petal_length_barplot.png    # Average petal length comparison chart
└── sepal_scatter_plot.png      # Sepal length vs width scatter plot by species
```

---

## 🛠️ Key Technical Steps & Implementation

### 1. Data Cleaning & Preprocessing (Task 1)
* **Loading Data**: Loaded CSV datasets robustly in Google Colab using `pandas.read_csv()`.
* **Missing Value Handling**: Scanned for null values and applied mean/mode imputation.
* **Duplicate Removal**: Checked for duplicate records and cleaned dataframe indices.
* **Standardization**: Standardized column headers to lowercase with snake_case and normalized categorical species strings (`setosa`, `versicolor`, `virginica`).

### 2. Exploratory Data Analysis & Statistics (Task 2)
* **Summary Statistics**: Computed central tendency and dispersion metrics (mean, median, mode, standard deviation, min, max, percentiles) using `.describe()`.
* **Correlation Matrix**: Evaluated feature linear relationships, identifying strong positive correlations between petal length and petal width ($r pprox 0.96$).
* **Outlier Detection**: Utilized grouped boxplots across species to inspect data spreads and outliers.

### 3. Data Visualization (Task 3)
* **Bar Plots**: Visualized average petal lengths per species using custom color palettes.
* **Scatter Plots**: Mapped sepal length against sepal width with hue-based species separation and customized legends.
* **Image Export**: Exported high-resolution `.png` figures (`dpi=300`) for professional reporting.

---

## 🚀 How to Run in Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `1) iris.csv` dataset and script cells.
3. Run the blocks sequentially to replicate the data cleaning pipeline and generate plots.

---
*Created by Isaac Salifu Nortey Tetteh | BSc. Mathematics and Statistics, University of Cape Coast* [cite: 2026-07-10]
