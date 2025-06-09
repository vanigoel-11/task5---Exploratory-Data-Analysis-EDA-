# 🧠 Exploratory Data Analysis (EDA) - Task 5

This repository contains a Jupyter Notebook that performs detailed exploratory data analysis (EDA) on a structured dataset. The goal is to understand the data, visualize key patterns, and summarize important insights for further modeling or business decisions.

---

## 📂 Files

- `task 5.ipynb`: Original notebook with analysis and visualizations
- `task 5_with_observations.ipynb`: Enhanced notebook with written observations after each visual
- `README.md`: Documentation for GitHub repository

---

## 📊 What’s Inside?

The notebook performs the following steps:

### ✅ Data Overview
- `.info()`, `.describe()`, and `.value_counts()` used to inspect structure, summary statistics, and categorical distributions.

### ✅ Visualizations
- `sns.pairplot()` — pairwise feature relationships
- `sns.heatmap()` — correlation matrix
- Histograms, boxplots, and scatterplots for understanding feature distributions, outliers, and relationships

### ✅ Observations
- Written markdown observations are added after each visual
- Trends, correlations, and anomalies are discussed

### ✅ Summary
- A final section summarizes key findings from the EDA:
  - Feature correlations
  - Outliers
  - Skewed distributions
  - Class relationships and imbalances

---

## 🔧 Requirements

You can install the necessary dependencies using:

```bash
pip install pandas seaborn matplotlib notebook
