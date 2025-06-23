# 🫀 Heart Disease Dataset - Exploratory Data Analysis & Visualization

This project focuses on **Exploratory Data Analysis (EDA)** and **Data Visualization** of a heart disease dataset using Python. By leveraging visualization techniques such as histograms, pie charts, violin plots, heatmaps, and pair plots, we aim to uncover insights into how different variables affect the likelihood of heart disease.

---

## 📊 Project Overview

Data visualization is a powerful tool for understanding and communicating insights from datasets. In this project, we use various types of plots to:

- Identify patterns, trends, and relationships in heart disease data
- Explore the impact of age, cholesterol, gender, and more on heart disease
- Visually analyze data distributions and correlations

---

## 🧠 Skills & Tools Used

- **Python**
- **Pandas** – Data manipulation
- **Matplotlib** – Static plotting
- **Seaborn** – Advanced statistical visualizations
- **Kaggle** – Dataset hosting and notebook environment

---

## 📂 Dataset Details

- **Name:** Heart Disease Dataset  
- **Size:** ~15 KB (CSV format)  
- **Columns:**  
  - `Age`, `Sex`, `ChestPainType`, `RestingBP`, `Cholesterol`, `FastingBS`, `RestingECG`, `MaxHR`, `ExerciseAngina`, `Oldpeak`, `ST_Slope`, `HeartDisease`  
- **Source:** [Kaggle Dataset](https://www.kaggle.com)

---

## 🧩 Project Structure

This project is divided into the following parts:

### 1. 📥 Introduction & Setup on Kaggle
- Introduction to the Kaggle platform
- Dataset loading and overview
- Column inspection and understanding dataset structure  
🔗 [Kaggle Notebook Link](#)

---

### 2. 📈 Age Distribution - DistPlot
- Seaborn's `distplot` to visualize age distribution
- Histogram and KDE for age analysis  
🔗 [Code](#)

---

### 3. 🥧 Categorical Variables - Pie Charts
- Pie charts for visualizing:
  - Gender distribution
  - Chest Pain Type
  - Heart Disease presence  
🔗 [Code](#)

---

### 4. 🎻 Violin Plot Analysis
- Visual comparison of numeric data across groups
- Violin plots for:
  - Age vs Heart Disease
  - Gender vs Heart Disease
  - Cholesterol & BP analysis  
🔗 [Code](#)

---

### 5. 🔥 Correlation Matrix - HeatMap
- Pearson correlation matrix of numerical features
- Heatmap to identify strongly related variables  
🔗 [Code](#)

---

### 6. 🔍 Correlation - JointPlot
- Joint distribution and regression line
- Relationship analysis between:
  - Age vs Max HR
  - Max HR vs Heart Disease  
🔗 [Code](#)

---

### 7. 🧮 Correlation - PairPlot
- Matrix of scatter plots for all numeric columns
- Regression trend lines to visualize inter-variable relationships  
🔗 [Code](#)

---

## ✅ Prerequisites

Ensure the following libraries are installed:

```bash
pip install pandas matplotlib seaborn
```

### 💡 Key Insights
  - Age group 40–70 is most represented in heart disease data.

  - Males have a higher occurrence of heart disease.

  -  Some variables like cholesterol and max heart rate show strong correlation with heart disease.

  - Visual tools like heatmaps and violin plots can effectively communicate relationships.

##  Author
Dilkhush Yash– Data Visualization & Analysis
