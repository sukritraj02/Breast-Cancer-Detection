# 🩺 Breast Cancer Detection

## 📘 Overview
This project aims to build a *machine learning model* that detects whether a tumor is *malignant* or *benign* based on medical diagnostic data.  
It demonstrates the full pipeline — from *data preprocessing* and *model training* to *evaluation and deployment* — using Python and scikit-learn.

---

## ⚙ Technologies Used
- *Python 3.12*
- *Pandas, NumPy* – data handling  
- *Scikit-learn* – model training & evaluation  
- *Matplotlib / Seaborn* – visualization  
- *Jupyter Notebook* – development environment  

---

## 🧠 Workflow
1. *Data Preprocessing*
   - Cleaned and encoded dataset  
   - Handled missing values and normalized features  

2. *Model Training*
   - Used *Logistic Regression* as a baseline model  
   - Split dataset into training and test sets  
   - Evaluated performance using accuracy and confusion matrix  

3. *Model Saving*
   - Serialized the trained model using pickle as model.pkl  

---

## 🧩 How to Run
```bash
git clone https://github.com/sukritraj02/Breast-Cancer-Detection.git
cd Breast-Cancer-Detection
pip install -r requirements.txt
jupyter notebook
