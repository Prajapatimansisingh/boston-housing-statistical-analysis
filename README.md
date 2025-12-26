# Boston Housing Statistical Analysis

## 📌 Project Overview
This project analyzes housing price data collected by the U.S. Census Service for Boston, MA.
The objective is to apply statistical analysis and data visualization techniques to extract
meaningful insights that support data-driven decision-making.

---

## 🧠 Business Context
You are a Data Scientist working for a housing agency in Boston. Management is interested in
understanding the key factors that influence housing prices and whether certain characteristics
(such as proximity to the Charles River, industrialization, and accessibility to employment centers)
have a statistically significant impact on home values.

---

## 📊 Dataset Description
The dataset includes the following key variables:
- **MEDV**: Median value of owner-occupied homes
- **CHAS**: Charles River dummy variable (1 = bounded by river, 0 = not bounded)
- **AGE**: Proportion of owner-occupied units built before 1940
- **NOX**: Nitric oxide concentration
- **INDUS**: Proportion of non-retail business acres per town
- **DIS**: Weighted distance to five Boston employment centers
- **PTRATIO**: Pupil-teacher ratio

---

## 🔍 Analysis Performed

### 1. Data Understanding & Quality Checks
- Displayed first five rows of the dataset
- Checked data types, missing values, and duplicates
- Examined correlation matrix

### 2. Exploratory Data Analysis
- Descriptive statistics of all numerical variables
- Boxplot analysis of MEDV
- Bar plot of CHAS variable
- MEDV comparison across AGE groups
- Scatter plot analysis of NOX vs INDUS
- Distribution analysis of PTRATIO

### 3. Statistical Testing
- **Levene’s Test** for equality of variances (MEDV vs CHAS)
- **Independent T-Test** to compare MEDV for river-bounded vs non-river homes
- **One-way ANOVA** to compare MEDV across AGE groups
- **Pearson Correlation Test** to assess relationship between NOX and INDUS

### 4. Regression Analysis
- Built a simple linear regression model to evaluate the impact of distance to employment centers (DIS) on MEDV
- Interpreted regression coefficients, significance, and model fit

---

## 📈 Key Insights
- Homes bounded by the Charles River tend to have higher median values
- Older housing areas generally show lower housing prices
- Higher industrial land use is associated with increased air pollution
- Distance from employment centers has a statistically significant impact on housing prices

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy
- Statsmodels

---

## 📁 Repository Contents
- `FinalProject_Boston Housing.ipynb` – Jupyter notebook containing full analysis
- `README.md` – Project documentation

---

## 🚀 Conclusion
This project demonstrates the application of statistical methods and exploratory data analysis
to real-world housing data, providing actionable insights for stakeholders and decision-makers.
