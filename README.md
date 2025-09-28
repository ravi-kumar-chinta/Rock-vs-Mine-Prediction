# SONAR Rock vs Mine Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

---

## 🚀 Introduction
This project builds a **machine learning model** to classify sonar signals as either **Rock (R)** or **Mine (M)** based on frequency response.

**Project Highlights:**
- Predicts the nature of the object (Rock or Mine) using **Logistic Regression**.
- Dataset: 208 instances, 60 numerical features representing sonar energy readings.
- Tools: **Python**, **Scikit-learn**, **NumPy**, **Pandas**.

---

## 📊 Dataset
- **Rows:** 208  
- **Features:** 60 numerical feature columns  
- **Label:** 1 column (`R` for Rock, `M` for Mine)  
- Features represent the energy reflected at different frequencies.  

---

## ⚙️ Installation & Setup
1. **Clone the repository:**
```bash
git clone https://github.com/ravi-kumar-chinta/Rock-vs-Mine-Prediction.git
```
2. **Install required libraries:**
```bash
pip install numpy pandas scikit-learn

```

3. **Run the notebook:**
Open the provided Jupyter/Colab notebook and run all cells.

---

## 🛠️ Project Workflow

1. **Data Loading:** Load the dataset into a pandas DataFrame.

2. **Data Preprocessing:** Separate features (X) and labels (Y).

3. **Train-Test Split:** Split the data (e.g., 90% train, 10% test).

4. **Model Training:** Train a Logistic Regression model.

5. **Model Evaluation:** Evaluate accuracy on training and test sets.

6. **Predictive System:** Predict if a sonar signal is Rock (R) or Mine (M).

---
## 📈 Results
| Metric            | Accuracy |
| ----------------- | -------- |
| Training Accuracy | ~83%     |
| Test Accuracy     | ~83%     |
The model demonstrates effective classification for sonar signals.

---


