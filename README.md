# **Loan Approval Prediction**

## 📌 Project Overview

This project aims to predict loan approval status based on applicant details using Machine Learning techniques.
The dataset is sourced from **Kaggle** and contains various features such as applicant income, loan amount, credit history, and more.

The project is implemented in **Python** using Google Colab and includes the full data processing, exploratory analysis, and predictive modeling pipeline.

---

## 📂 Dataset

* **Source:** [Kaggle - Loan Approval Prediction Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset)
* **Format:** CSV file (`loan_approval_dataset.csv`)
* **Features Include:**

  * `ApplicantIncome`
  * `CoapplicantIncome`
  * `LoanAmount`
  * `Loan_Amount_Term`
  * `Credit_History`
  * `Property_Area`
  * and more...

---

## 🛠 Tools & Libraries

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical computations
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Machine Learning algorithms
* **Joblib** – Model saving/loading

---

## 🚀 Steps in the Project

1. **Import Libraries** – Load all required packages.
2. **Load Dataset** – Download from Kaggle and read into Pandas DataFrame.
3. **Data Cleaning & Preprocessing**

   * Handle missing values
   * Encode categorical variables
   * Scale numerical features
4. **Exploratory Data Analysis (EDA)** – Visualize trends and correlations.
5. **Model Training** – Train classification models to predict loan approval.
6. **Model Evaluation** – Use metrics such as accuracy, precision, recall, and confusion matrix.
7. **Model Saving** – Save the trained model using Joblib for later use.

---

## 📊 Expected Output

* Cleaned dataset ready for modeling.
* Visualizations showing trends in loan approvals.
* A trained ML model capable of predicting loan approval status.
* Saved model file for deployment.

---

## 💻 How to Run

1. Clone the repository or upload the notebook to **Google Colab**.
2. Upload your **Kaggle API key (`kaggle.json`)** to authenticate.
3. Run all cells in sequence.
4. View results and download the trained model.

---

## 📜 License

This project is for educational purposes as part of the **Elevvo Internship Program**.

---
