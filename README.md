# 🫀 Heart Disease Prediction

This project uses machine learning to predict the likelihood of heart disease based on a patient's health data. It demonstrates the process of data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation using real-world health data.

---

## 📌 Objective

To build a classification model that accurately predicts whether a patient is at risk of heart disease, using medical attributes such as age, cholesterol level, blood pressure, and more.

---

## 📊 Dataset

- **Source**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease) *(commonly used version from Kaggle)*
- **Rows**: 303
- **Features**: 14 medical attributes
  - age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, max heart rate, etc.
- **Target**: `1` (presence of heart disease), `0` (absence)

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🧹 Process

### 1. Data Cleaning
- Checked for missing values and data types
- Handled categorical features with label encoding

### 2. Exploratory Data Analysis (EDA)
- Correlation heatmaps
- Distribution plots (age, cholesterol, chest pain type)
- Boxplots to detect outliers

### 3. Feature Engineering
- Encoded categorical variables
- Normalized continuous features

### 4. Model Training & Evaluation
- Models tried:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - K-Nearest Neighbors (KNN)
- Evaluated with:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC Curve

---

## ✅ Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 85% |
| Random Forest | **88%** |
| Decision Tree | 81% |
| KNN | 83% |

- **Best Model**: Random Forest
- Good balance between recall and precision
- Feature importance analysis showed `cp` (chest pain type), `thal`, and `ca` (number of major vessels) as key indicators

---

## 📈 Visuals

<p align="center">
  <img src="images/heart_corr_heatmap.png" alt="Correlation Heatmap" width="500"/>
</p>

<p align="center">
  <img src="images/roc_curve_rf.png" alt="ROC Curve - Random Forest" width="500"/>
</p>

---

## 📌 Key Learnings

- How to preprocess structured health data
- Importance of EDA in understanding medical features
- How different classification models perform on imbalanced datasets
- How to evaluate a medical diagnosis model responsibly

---

## ▶️ How to Run

1. Clone this repo:
```bash
git clone https://github.com/1Chizey/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction

📬 Contact
Francis Chizey
Data Scientist  | Streamlit Developer
https://github.com/1Chizey | www.linkedin.com/in/francis-chizey-8838a5256 | chizeyfrancis@gmail.com
