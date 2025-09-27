# Heart Disease Classification

This project applies **Machine Learning techniques** to predict the presence of heart disease in patients based on clinical parameters. The goal is to assist in early detection and provide insights for better healthcare decision-making.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Using machine learning, we can analyze patient data and identify patterns that may indicate the presence of heart disease.
This project explores different classification models and evaluates their performance.

---

## 📂 Dataset

* **Source**: UCI Machine Learning Repository ([Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease))
* **Features**: Patient clinical parameters such as age, sex, blood pressure, cholesterol levels, etc.
* **Target**: Presence (1) or Absence (0) of heart disease.

---

## 🛠️ Tech Stack

* **Programming Language**: Python
* **Environment**: Jupyter Notebook
* **Libraries Used**:

  * `numpy`, `pandas` – Data manipulation
  * `matplotlib`, `seaborn` – Data visualization
  * `scikit-learn` – Machine learning models & evaluation

---

## 🔎 Exploratory Data Analysis (EDA)

* Checked missing values and data distribution
* Visualized feature correlations with heatmaps and plots
* Identified key features influencing heart disease prediction

---

## 🤖 Models Implemented

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* Gradient Boosting

Each model was trained, tested, and compared using metrics such as **Accuracy, Precision, Recall, and F1-score**.

---

## 📊 Results

* Best-performing model achieved **high accuracy (>80%)** on the test set.
* Random Forest and Gradient Boosting gave the most consistent performance.

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/heart-disease-classification.git
   cd heart-disease-classification
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook heart_disease_classification.ipynb
   ```

---

## 📌 Future Work

* Hyperparameter tuning for better accuracy
* Deployment using Flask/Streamlit for real-time predictions
* Expanding dataset for better generalization

---

## 📜 License

This project is licensed under the MIT License.

---
