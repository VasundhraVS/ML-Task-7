# 💳 Credit Card Fraud Detection Using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green" alt="Machine Learning"/>
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Project Status"/>
</p>

<p align="center">
  🔍 Detect suspicious transactions with Machine Learning!
</p>

---

## 📌 Table of Contents

- [🌟 About the Project](#-about-the-project)
- [🎯 Objectives](#-objectives)
- [🛠️ Technologies Used](#️-technologies-used)
- [📂 Dataset](#-dataset)
- [⚙️ How It Works](#️-how-it-works)
- [🤖 Machine Learning Model](#-machine-learning-model)
- [📊 Evaluation Metrics](#-evaluation-metrics)
- [📈 Visualizations](#-visualizations)
- [📁 Output Files](#-output-files)
- [🚀 How to Run](#-how-to-run)
- [💡 Future Enhancements](#-future-enhancements)

## 🌟 About the Project

Credit card fraud is a major challenge in digital payments. This project uses **Machine Learning** to classify credit card transactions as genuine or fraudulent.

A **Random Forest Classifier** is trained on transaction data and evaluated using several performance metrics and visualizations.

## 🎯 Objectives

- 🔎 Analyze credit card transaction data.
- 🧹 Prepare the dataset for machine learning.
- 🌳 Train a Random Forest classification model.
- 📊 Evaluate the model's performance.
- 🎯 Identify important features influencing predictions.
- 💾 Export actual fraudulent transactions from the test dataset.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming language |
| 🐼 Pandas | Data manipulation |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical visualization |
| 🤖 Scikit-learn | Machine learning and evaluation |
| 📓 Jupyter Notebook | Development environment |

## 📂 Dataset

**Dataset:** `creditcard.csv`

The dataset contains credit card transaction records, with the `Class` column representing the transaction type.

- ✅ `0` — Genuine transaction
- 🚨 `1` — Fraudulent transaction

The notebook examines the dataset, checks missing values, and analyzes the distribution of transaction classes before training the model.

> ⚠️ The dataset must be available at the file path specified in the notebook.

## ⚙️ How It Works

1. 📥 **Import Libraries** — Load the required Python libraries.
2. 📂 **Load Dataset** — Read the transaction data.
3. 🔍 **Explore Data** — Inspect columns, missing values, and class distribution.
4. 🧹 **Prepare Data** — Separate input features and target labels and remove rows containing missing values.
5. ✂️ **Split Data** — Use an 80:20 training and testing split with stratification.
6. 🌳 **Train Model** — Fit a Random Forest Classifier with 100 trees and balanced subsampling class weights.
7. 🔮 **Make Predictions** — Predict transaction classes and fraud probabilities.
8. 📊 **Evaluate Results** — Generate evaluation metrics and visualizations.
9. 🎯 **Analyze Features** — Identify the ten most important features.
10. 💾 **Export Results** — Save actual fraudulent test transactions to a CSV file.

## 🤖 Machine Learning Model

### 🌳 Random Forest Classifier

Random Forest is a supervised machine learning algorithm that combines predictions from multiple decision trees.

**Why use it?**

- 🌲 Combines multiple decision trees.
- 📊 Supports classification tasks.
- ⚖️ Can account for class imbalance using appropriate class weights.
- 🎯 Provides feature importance scores.

## 📊 Evaluation Metrics

| Metric | What it tells us |
|---|---|
| 🎯 Precision | How many predicted fraud cases were actually fraud |
| 🚨 Recall | How many actual fraud cases were detected |
| ⚖️ F1-Score | Balance between precision and recall |
| 📈 ROC-AUC | How well the model distinguishes fraud from genuine transactions |
| 🧮 Confusion Matrix | Counts correct and incorrect predictions |

## 📈 Visualizations

The notebook generates:

- 🧮 Confusion Matrix
- 🎯 Top 10 Important Features
- 📉 ROC Curve

These visualizations help understand the model's classification performance.

## 📁 Output Files

The notebook exports:

`actual_fraudulent_test_transactions.csv`

This file contains actual fraudulent transactions from the test dataset, along with their actual class, predicted class, and predicted fraud probability.

## 🚀 How to Run

1. 📥 Download or clone this repository.
2. 📓 Open `ML_Task_7.ipynb` in Google Colab or Jupyter Notebook.
3. 📂 Upload the `creditcard.csv` dataset.
4. 🛠️ Update the dataset path if necessary.
5. ▶️ Run all notebook cells.
6. 📊 Review the evaluation metrics and charts.
7. 💾 Download the generated CSV output.

## 💡 Future Enhancements

- ⚡ Build a real-time fraud detection interface.
- 🌐 Develop a web application for transaction analysis.
- 📊 Add an interactive fraud monitoring dashboard.
- 🔔 Generate alerts for suspicious transactions.
- 🧪 Compare Random Forest with other classification algorithms.

## 🎓 Learning Outcomes

Through this project, I explored:

- 🧹 Data preprocessing
- 🤖 Supervised machine learning
- 🌳 Random Forest classification
- 📊 Model evaluation
- 📈 Feature importance analysis
- 💾 Exporting prediction results

## 👩‍💻 Author

**Vasundhra V S**

💻 Interested in Machine Learning, Data Analytics, and Web Development.

---

<p align="center">
  ⭐ If you find this project interesting, consider giving the repository a star!
</p>

<p align="center">
  💙 Thank you for visiting my project! Keep learning and keep building. 🚀
</p>
