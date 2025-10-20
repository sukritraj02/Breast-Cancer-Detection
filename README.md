# 🩺 Breast Cancer Detection

## 📘 Overview
This project aims to build a **machine learning model** that detects whether a tumor is **malignant** or **benign** based on medical diagnostic data.  
It demonstrates the full pipeline — from **data preprocessing** and **model training** to **evaluation and deployment** — using Python and scikit-learn.

---

## ⚙️ Technologies Used
- **Python 3.12**
- **Pandas, NumPy** – data handling  
- **Scikit-learn** – model training & evaluation  
- **Matplotlib / Seaborn** – visualization  
- **Jupyter Notebook** – development environment  

---

## 🧠 Workflow
1. **Data Preprocessing**
   - Cleaned and encoded dataset  
   - Handled missing values and normalized features  

2. **Model Training**
   - Used **Logistic Regression** as a baseline model  
   - Split dataset into training and test sets  
   - Evaluated performance using accuracy and confusion matrix  

3. **Model Saving**
   - Serialized the trained model using `pickle` as `model.pkl`  

---

## 🧩 How to Run
```bash
git clone https://github.com/sukritraj02/Breast-Cancer-Detection.git
cd Breast-Cancer-Detection
pip install -r requirements.txt
jupyter notebook
Open Model_Development.ipynb, run all cells, and view predictions.
```
👥 Team Members & Contributions
Name	GitHub	Responsibilities
Sukrit Raj	@sukritraj02	Data preprocessing, model development, and final integration
Ayushi Kumari	@imayushi001	Exploratory data analysis (EDA), visualizations, and report preparation
Anamika Patel	@Anamikapatel01	Model evaluation, performance tuning, and documentation

📊 Results
Achieved high classification accuracy on test data

Model successfully predicts malignant vs. benign with strong precision and recall

📄 License
This project is open-source under the MIT License.

💡 Future Work
Experiment with advanced models (Random Forest, SVM, XGBoost)

Build a simple Flask/Streamlit web app for real-time predictions

Perform hyperparameter tuning for better generalization

Developed with ❤️ by Sukrit Raj, Ayushi Kumari, and Anamika Patel







