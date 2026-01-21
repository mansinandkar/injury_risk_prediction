# Injury Risk Prediction in Athletes

This project explores machine learning–based prediction of injury risk in athletes using structured data analysis and predictive modeling techniques.

Sports injuries can significantly impact athlete performance and career longevity. The goal of this project is to identify patterns and risk factors from athlete performance and workload data that are associated with injury occurrences and to build models capable of predicting injury risk. This work combines data preprocessing, exploratory analysis, feature engineering, and machine learning modeling to provide actionable insights for injury prevention and athlete health monitoring.

---

## 🚀 Project Objectives

- Understand athlete injury data and preprocess it for analysis
- Explore key factors and metrics related to athlete injuries
- Train and evaluate machine learning models to predict injury risk
- Compare model performance and identify impactful features
- Provide insights that could help coaches and sports scientists mitigate injury risk

---

## 📦 Dataset

- About the dataset - [mHealth Dataset](data/README.md)
- [mHealth Train Dataset](https://drive.google.com/file/d/1C81zpnyhMJL-tinuEf6rPq6EBVU8pUXD/view?usp=drive_link)
- [mHealth Test Dataset](https://drive.google.com/file/d/1p5SgLKhm1DQrtDZr-2wuvrBGPwy2-BQw/view?usp=drive_link))

---

## 📌 Methodology

### 1. **Data Integration & Cleaning**
- Combined raw datasets where necessary (e.g., workload + injury records)
- Handled missing values and data consistency issues
- Performed exploratory analysis to understand feature distributions

### 2. **Exploratory Data Analysis (EDA)**
- Visualized injury occurrence trends across athletes
- Analyzed distributions of key workload and performance metrics
- Inspected feature correlations and class balance

### 3. **Feature Engineering**
- Derived additional metrics such as weekly and accumulated workload
- Scaled and prepared features for ML modeling
- Identified features likely to correlate with injury risk

### 4. **Model Training & Evaluation**
Different classification models were trained to predict injury status, including:

- Logistic Regression
- Decision Trees
- Ensemble methods (e.g., Bagging Classifier)
- Other relevant models depending on project focus

Model performance was evaluated using standard metrics such as:
- Accuracy
- Confusion Matrix
- F1-score

---

## 📈 Results & Insights

- Machine learning models demonstrated the ability to predict injury risk reasonably well based on workload and performance data.
- Ensemble methods (e.g., Bagging Classifier) tended to outperform basic models in accuracy and F1-score.
- Key workload and performance metrics contributed significantly to injury risk estimation.

---

## 🛠 Tools & Technologies

This project leverages the following stack:

- **Python** — data processing and modeling
- **Pandas & NumPy** — data manipulation
- **scikit-learn** — machine learning models and evaluation
- **Matplotlib / Seaborn** — visualizations
- **Jupyter Notebooks** — interactive exploration and demoing

---



