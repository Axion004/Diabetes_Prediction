# AI-Powered Diabetes Prediction

A machine learning-based solution for predicting diabetes using structured medical data. This project uses advanced classification techniques to build a reliable, optimized model for early diagnosis support.

## 🔧 Technologies Used

- Python  
- Scikit-learn  
- Support Vector Machine (SVM)  
- Random Forest  
- SMOTE (Synthetic Minority Over-sampling Technique)  
- GridSearchCV  

## 📊 Overview

The project leverages the PIMA Indian Diabetes Dataset and applies preprocessing, model selection, hyperparameter tuning, and evaluation to deliver accurate predictions. SMOTE is used to handle class imbalance, while GridSearchCV ensures optimal model performance.

## ⚙️ Features

- Handles imbalanced medical data using SMOTE  
- Applies and compares multiple classifiers (SVM, Random Forest)  
- Performs hyperparameter tuning with GridSearchCV  
- Evaluates model performance using accuracy, precision, recall, F1-score, and confusion matrix  

## 📁 Project Structure

```

├── data/              # Dataset (PIMA diabetes dataset or a link)
├── notebooks/         # Jupyter notebooks for analysis and modeling
├── src/               # Source code for model training, preprocessing
├── results/           # Output graphs, confusion matrices, metrics
├── LICENSE
├── README.md
└── requirements.txt

````

## 🚀 Getting Started

1. Clone the repo:
```bash
git clone https://github.com/yourusername/diabetes-prediction.git
cd diabetes-prediction
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook or Python script to train the model.

## 📜 License

This project is licensed under the [MIT License](./LICENSE).

---

*Contributions and feedback are welcome!*
