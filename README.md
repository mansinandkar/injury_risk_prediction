# Injury Risk Prediction in Athletes using ML and DL

This project explores machine learning and deep learning –based prediction of injury risk in athletes using structured data analysis and predictive modeling techniques.

Sports injuries can significantly impact athlete performance and career longevity. The goal is to identify injury-related patterns from athlete workload and sensor-derived data and evaluate predictive performance using robust classification metrics. The workflow includes data preprocessing, exploratory analysis, feature engineering, class imbalance handling, and model evaluation across multiple algorithms. 

---

## 🚀 Project Objectives

- Perform exploratory data analysis (EDA) to understand injury patterns and class imbalance
- Engineer and scale features suitable for ML and deep learning models
- Handle class imbalance using resampling techniques (SMOTE)
- Train and compare classical ML models and neural networks
- Evaluate models using precision, recall, F1-score, and ROC-AUC

---

## 📦 Dataset

The project uses the **mHealth dataset**, which contains multi-sensor time-series data collected from athletes during physical activity.

- Data is split into training and testing sets
- Injury labels are highly imbalanced, requiring resampling techniques
- Feature matrices are reshaped appropriately for classical ML and sequence-based deep learning models

- About the dataset - [mHealth Dataset](data/README.md)
- [mHealth Train Dataset](https://drive.google.com/file/d/165DywUbgKTEzJUNDAwK4m3A9ZNOWtLMn/view?usp=drive_link)
- [mHealth Test Dataset](https://drive.google.com/file/d/1OH0ENhsJbLAbNO-bW0Ia0Dj1j08lxarf/view?usp=drive_link)

---

## 📌 Methodology

### 1. Data Cleaning & Preparation
- Missing value handling and normalization
- Feature scaling using StandardScaler
- Class imbalance handling using SMOTE

### 2. Exploratory Data Analysis (EDA)
- Injury class distribution analysis
- Feature correlation and distribution visualization
- Identification of dominant injury-related signals

### 3. Model Training
The following models were implemented and evaluated:

**Classical Machine Learning**
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

**Deep Learning**
- LSTM-based sequence models (TensorFlow/Keras)
- 1D Convolutional Neural Networks (PyTorch)

### 4. Evaluation
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC and Precision–Recall curves

---

## 📈 Results & Insights

- Class imbalance significantly affected baseline model performance and was mitigated using SMOTE
- Ensemble and margin-based models (Random Forest, SVM) outperformed basic linear classifiers
- Deep learning models (LSTM, 1D-CNN) demonstrated the ability to capture temporal patterns in sensor data
- Precision–Recall tradeoffs were analyzed to prioritize injury detection over false negatives

---

## 🛠 Tools & Technologies

**Programming & Environment**
- Python
- Jupyter Notebook
- Google Colab

**Data Processing**
- Pandas
- NumPy
- SciPy

**Machine Learning**
- scikit-learn (Logistic Regression, Random Forest, SVM, Pipelines)
- imbalanced-learn (SMOTE)

**Deep Learning**
- TensorFlow / Keras (LSTM)
- PyTorch (1D-CNN)

**Visualization & Evaluation**
- Matplotlib
- Seaborn

---

## 🤝 Contributors
- Mansi Nandkar
- Reshma Panibhate
- Anuj Abhay Joshi
- Akanksh Rao S R

