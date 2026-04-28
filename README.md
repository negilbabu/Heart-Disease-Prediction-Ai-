<h1 align="center">
  CardioGuard | Heart Disease Predictive System 🫀🤖
</h1>

<p align="center">
  <strong>An AI-driven diagnostic tool utilizing clinical vital signs to predict cardiovascular disease risk with high precision.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MSc_AI-Academic_Project-blue?style=for-the-badge" alt="Academic Context" />
  <img src="https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Library-Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/Diagnostics-Healthcare_AI-success?style=for-the-badge" alt="Healthcare AI" />
</p>

---

## 📖 Project Overview

This project was developed during my **MSc in Artificial Intelligence at Berlin School of Business and Innovation (BSBI)**. The core objective is to apply Machine Learning algorithms to identify patterns in clinical data that indicate the onset of heart disease. By analyzing vital information such as cholesterol levels, blood pressure, and heart rate, this system provides a data-driven layer of support for early medical intervention.

## 🚀 Clinical AI Pipeline

The system implements a rigorous medical data science workflow:

- **Data Ingestion & Cleaning:** Processing standardized clinical datasets (e.g., UCI Heart Disease) with focus on handling outliers and missing values in critical vitals.
- **Feature Importance Analysis:** Identifying which medical metrics (e.g., thal, ca, cp) have the highest correlation with cardiovascular risk.
- **Predictive Modeling:** Comparison of multiple classification algorithms (Logistic Regression, K-Nearest Neighbors, Random Forest) to determine the most reliable diagnostic baseline.
- **Precision Optimization:** Fine-tuning hyperparameters to minimize "False Negatives," which is critical in a life-safety healthcare context.
- **Model Evaluation:** Detailed performance benchmarking using Accuracy, Precision, Recall, and ROC-AUC metrics.

---

## 🛠️ Technology Stack

| Layer | Technology | Usage |
| :--- | :--- | :--- |
| **Language** | **Python** | Core implementation language. |
| **ML Framework**| **Scikit-Learn** | Pipeline creation, model training, and evaluation. |
| **Data Handling**| **Pandas / NumPy** | Numerical processing of patient records. |
| **Visualization**| **Matplotlib / Seaborn** | Generating medical correlation heatmaps and ROC curves. |
| **Environment** | **Jupyter Notebook** | Transparent, documented research environment. |

---

## ✨ Key Technical Features

- **High-Recall Focus:** The models are optimized for high recall to ensure potential heart conditions are not overlooked.
- **Interpretability:** Implementation of feature importance mapping to explain *why* the AI predicted a specific risk level.
- **Robust Scaling:** Automated scaling of vital signs (e.g., resting blood pressure) to ensure consistency across different patient demographics.

---

## 🚀 Getting Started

### Prerequisites
* Python 3.9+
* Jupyter Notebook or Google Colab

### Installation & Execution
1. Clone the repository:
   ```bash
   git clone [https://github.com/negilbabu/heart-disease-prediction-ai.git](https://github.com/negilbabu/heart-disease-prediction-ai.git)

2. Install required Libraries:
    ```bash
    pip install pandas scikit-learn seaborn matplotlib
3. Run the analytical Notebook:
    ```bash
   jupyter notebook Heart_Disease_Prediction.ipynb

🎓 Academic Context
  
  This project was completed as part of the machine learning modules of my Master of Science in Artificial Intelligence (MSc AI) at BSBI. It explores the intersection of algorithmic efficiency and clinical reliability in regulated industries.


📄 License
  
  This project is licensed under the MIT License.
