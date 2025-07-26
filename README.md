🏦 Loan Approval Prediction
This project aims to predict whether a loan application will be Approved or Rejected using customer financial and asset data. It walks through the complete machine learning pipeline — from data preprocessing and visualization to model training and evaluation using a Random Forest Classifier.

---

## 📂 Project Structure

- `main_notebook.ipynb` – Full Jupyter Notebook with code, EDA, and model
- `dataset.csv` – Dataset used for training the model 
- `README.md` – Project overview and guide

---

## 📊 Dataset Overview

- Size: 4269 rows × 13 columns
- Features:
  education, self_employed, income_annum, loan_amount, loan_term, cibil_score
  Asset values: residential, commercial, luxury, bank
- Target: loan_status (Approved / Rejected)

---

 ## 🔧 Data Cleaning & Feature Engineering
- Removed unnecessary column (loan_id)
- Verified no missing or duplicate values
- Label encoding of categorical features
- Created new columns:
- income_per_month(lac)
- loan_amount(lac)
- Asset values in lakhs
- Dropped redundant original columns after transformation

> 📌 **Dataset Source:**  
> [https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset]  
> *(I do not own this dataset — used for educational purposes only)*

---

## 📊 Exploratory Data Analysis

- 📌 Visualized class distribution of loan_status
- 📉 Histograms of numeric features
- 📊 Multi-variate analysis using scatter plots
- 📈 Grouped analysis of features by loan status
-🔎 Found CIBIL score as the most influential feature for approval

---

## 🧠 Model Used

- **Model:** Random Forest Classifier
- **Target:** Loan Status
- **Accuracy:** ~98% on test set

---

## 🛠️ Tools & Technologies

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Scikit-learn
- Random Forest Classifier

---

## 📌 Key Takeaways

- Building an end-to-end machine learning pipeline
- Feature engineering from raw financial data
- Visualizing and interpreting data relationships
- Understanding the impact of credit score and loan amount on approvals
- Evaluating model performance and interpreting feature importance


---

## 📫 Contact

**Muhammad Umar Saleem**  
Electrical Engineering Graduate (June 2025)  
Aspiring Data Scientist | ML Enthusiast  
