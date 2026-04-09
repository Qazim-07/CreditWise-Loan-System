# CreditWise Loan System

## 📌 Overview
CreditWise Loan System is a **machine learning project** designed to predict loan approval outcomes based on applicant data. It demonstrates an end-to-end supervised ML pipeline using **k-Nearest Neighbors (kNN)**, **Logistic Regression**, and **Naive Bayes** classifiers.  

This project is ideal for **students, beginners, and enthusiasts** who want to learn how to build, train, and evaluate classification models in Python using Jupyter Notebook.

---

## 🎯 Objectives
- Predict whether a loan application will be approved or rejected.
- Compare performance of multiple ML algorithms.
- Provide a clear, step-by-step workflow for beginners in machine learning.

---

## 📂 Project Structure

CreditWise-Loan-System/
│── README.md                # Project documentation
│── credit_wise.ipynb        # Jupyter Notebook with ML pipeline
│── loan_approval_data.csv   # Dataset used for training/testing


## 📊 Dataset
- **File:** `loan_approval_data.csv`  
- **Features (example):**
  - Applicant Income
  - Loan Amount
  - Credit History
  - Education
  - Employment Status
  - Gender
  - Marital Status
- **Target Variable:** Loan Approval (Yes/No)

> Note: The dataset is structured for educational purposes and may not represent real-world banking data.


## ⚙️ Technologies Used
- **Python 3.x**
- **Jupyter Notebook**
- **Libraries:**
  - `pandas` → Data handling
  - `numpy` → Numerical operations
  - `scikit-learn` → ML models & evaluation
  - `matplotlib` / `seaborn` → Visualization


## 🚀 Workflow
1. **Data Loading** → Import dataset using Pandas.  
2. **Exploratory Data Analysis (EDA)** → Check distributions, missing values, correlations.  
3. **Data Preprocessing** → Handle missing values, encode categorical variables, normalize features.  
4. **Model Training** → Train kNN, Logistic Regression, and Naive Bayes classifiers.  
5. **Model Evaluation** → Compare accuracy, precision, recall, F1-score, confusion matrix.  
6. **Results Visualization** → Plot graphs for performance comparison.  


## 📈 Example Results
- **Logistic Regression:** ~85% accuracy  
- **Naive Bayes:** ~82% accuracy  
- **kNN:** ~78% accuracy  

*(Results may vary depending on preprocessing and hyperparameters.)*


## 🔮 Future Improvements
- Add **hyperparameter tuning** (GridSearchCV, RandomizedSearchCV).  
- Implement **ensemble models** (Random Forest, XGBoost).  
- Deploy via **Flask/Django API** or **Streamlit dashboard**.  
- Expand dataset with more real-world features.  


## 🧑‍💻 How to Run
1. Clone the repository:
   
   git clone https://github.com/Qazim-07/CreditWise-Loan-System.git

2. Navigate to the folder:
   
   cd CreditWise-Loan-System
   
3. Install dependencies:
   
   pip install -r requirements.txt
   
4. Open Jupyter Notebook:
   
   jupyter notebook credit_wise.ipynb
   



## 🤝 Contributing
Contributions are welcome!  
- Fork the repo  
- Create a new branch  
- Commit changes  
- Submit a pull request  


## 👤 Author
- **Qazim-07**  
- GitHub: [Qazim-07](https://github.com/Qazim-07)
