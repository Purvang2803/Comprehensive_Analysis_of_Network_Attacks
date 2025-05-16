
# 📊 Comprehensive Analysis of Network Attacks Dataset

This repository contains a Jupyter notebook performing a detailed analysis and classification of network traffic data, distinguishing between benign and malicious activity using machine learning.

---

## 🔗 Dataset Used

This project utilizes the [UNSW-NB15 dataset](https://research.unsw.edu.au/projects/unsw-nb15-dataset), created by the Australian Centre for Cyber Security (ACCS) at UNSW Canberra.

The dataset contains modern normal activities and synthetic contemporary attack behaviors, designed for training and evaluating intrusion detection systems.

---

## 📁 Contents

* `Comprehensive_Analysis_of_Network_Attacks_Dataset.ipynb`: The complete notebook with data preprocessing, visualization, and classification.

---

## 🎯 Objective

To analyze and classify network traffic data using machine learning techniques and understand the key features that influence attack detection.

---

## 🛠️ Libraries Used

The following Python libraries are used in this notebook:

* `pandas` — for data manipulation
* `matplotlib` & `seaborn` — for data visualization
* `sklearn` — for preprocessing, model training, and evaluation
* `xgboost` — for high-performance gradient boosting
* `shap` — for model explainability
* `os` — for file handling

---

## 🔍 Key Steps

1. **Data Loading & Cleaning**: Handles missing values, drops irrelevant columns, and prepares features for modeling.
2. **EDA**: Visualizes distributions, correlations, and class balance.
3. **Feature Engineering**: Selects important features and encodes data.
4. **Modeling**: Trains models like Random Forest, XGBoost and evaluates them using metrics like accuracy and F1-score.
5. **Explainability**: Uses SHAP to understand model predictions.

---

## 📈 Results

Models achieve high accuracy and balanced F1-scores across classes, effectively distinguishing between attack types.

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/network-attacks-analysis.git
   cd network-attacks-analysis
   ```

2. Install the required libraries:

   ```bash
   pip install pandas matplotlib seaborn scikit-learn xgboost shap
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook Comprehensive_Analysis_of_Network_Attacks_Dataset.ipynb
   ```

---

