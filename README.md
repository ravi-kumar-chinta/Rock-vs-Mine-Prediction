# SONAR Rock vs Mine Prediction using Machine Learning

## Introduction
This project builds a **machine learning model** to classify sonar signals as either **Rock (R)** or **Mine (M)** based on frequency response.  

- Dataset: 208 instances with 60 numerical features representing energy reflected at different frequencies.  
- Goal: Predict the nature of the object (Rock or Mine) using **Logistic Regression**.  
- Tools: **Python**, **Scikit-learn**, **NumPy**, **Pandas**  

## Key Highlights
- Data loading and preprocessing  
- Train-test split for model evaluation  
- Model training using **Logistic Regression**  
- Accuracy evaluation on training and test sets  
- Predictive system for custom input  

## Dataset
- 208 rows, 60 numerical feature columns, and 1 label column (`R` for Rock, `M` for Mine)  
- Features represent sonar energy readings at different frequencies  

## Installation / Setup
1. Clone the repository or download the files:  
```bash
git clone https://github.com/ravi-kumar-chinta/Rock-vs-Mine-Prediction
```
2. Install required libraries:
```bash
pip install numpy pandas scikit-learn
```
3. Open the provided Jupyter/Colab notebook and run the cells.

--- 

## Project Workflow

1. Data Loading – Load the dataset into a pandas DataFrame.
2. Data Preprocessing – Separate features (X) and labels (Y).
3. Train-Test Split – Split the data (e.g., 90% train, 10% test).
4. Model Training – Train a Logistic Regression model.
5. Model Evaluation – Evaluate accuracy on training and test sets.
6. Predictive System – Predict if a sonar signal is a Rock (R) or Mine (M).

--- 

## Results
- Training Accuracy: ~83%

- Test Accuracy: ~83%

- The model demonstrates effective classification for sonar signals.

---

License
This project is open-source under the MIT License.