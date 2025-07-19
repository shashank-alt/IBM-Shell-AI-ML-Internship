# 🌍 Emissions Analysis using 2015 Summary Commodity Dataset (IBM Internship Project)

This repository contains an Exploratory Data Analysis (EDA) performed on the **"Supply Chain Emission Factors for US Industries and Commodities - 2015 Summary Commodity"** dataset provided as part of the IBM Edunet AI/ML Green Skills Internship Program.

---
## 🧠 Project Objective

To understand and visualize the trends and relationships in IBM Shell's stock performance by:
- Analyzing key metrics (Open, Close, High, Low, Volume)
- Identifying seasonal trends
- Exploring correlations
- Creating insightful visualizations
  
---
## 📦 Dataset Overview

- **Source**: IBM/EDUNET-provided CSV dataset
- **Year Covered**: 2015
- **Scope**: Emissions data for U.S. industries and commodities across various greenhouse gases.
- **Total Rows**: 264
- **Columns**:
  - `Commodity Name`: Name of the commodity
  - `Substance`: Greenhouse gas emitted (e.g., CO2, CH4, N2O, etc.)
  - `Unit`: Emission unit (kg, g, etc.)
  - `Supply Chain Emission Factors` (with/without margins): Core values showing emissions
  - Data Quality (DQ) metrics like:
    - `DQ ReliabilityScore`
    - `DQ TemporalCorrelation`
    - `DQ GeographicalCorrelation`
    - `DQ TechnologicalCorrelation`

---

## 📊 Exploratory Data Analysis (EDA)

The EDA was performed using **Python**, leveraging **Pandas**, **Seaborn**, and **Matplotlib**.

### 🔍 1. Initial Checks & Cleaning
- Viewed data shape, columns, types, basic stats
- Checked for:
  - Missing values
  - Duplicate rows
  - Unnecessary columns (e.g., dropped `Unnamed: 7`)

---

### 📉 2. Visualizations & Analysis

#### ✅ Bar Plot:
- **Substance-wise emission comparison**
- Helps identify which greenhouse gases dominate emissions

#### ✅ Histogram:
- Distribution of the `Supply Chain Emission Factors with Margins`
- Plots frequency & density (KDE)

#### ✅ Pie Chart:
- Proportion of emissions by **Substance**
- Shows which gas contributes most to overall emissions

#### ✅ Boxplot:
- Outlier detection in emission factors
- Visualizes spread and distribution

#### ✅ Correlation Heatmap:
- Matrix of correlation among numerical fields (like DQ scores and emission values)
- Useful for feature relationships or redundancy checks

#### ✅ Top Emitters (Bar Chart):
- Top 10 commodities or substances contributing the most emissions

#### ✅ Commodity-Wise Analysis:
- Groups emission values by `Commodity Name`
- Visualizes top 10 most polluting commodities


## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly (if used)

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ibm-shell-eda.git
   cd ibm-shell-eda
Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

Launch the notebook:

   ```bash
   jupyter notebook IBM_SHELL_EDA.ipynb
   ```
---

## 📝 Future Enhancements
Incorporate predictive modeling (e.g., ARIMA, LSTM)

Add interactive dashboards using Plotly/Dash

Automate data fetching from APIs (e.g., Yahoo Finance)

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

Author: Shashank
Institution: Bharati Vidyapeeth College of Engineering-Delhi
Graduation: 2026


---
