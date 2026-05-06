# 📊 Task 1: Data Pipeline Development

## 🚀 Overview
This project demonstrates the development of an automated data preprocessing pipeline for customer churn data. The pipeline transforms raw, unstructured data into a clean and machine learning-ready format using Python and Scikit-learn.

---

## 🎯 Objective
To design a reusable data pipeline that:
- Cleans raw data  
- Handles missing values  
- Encodes categorical variables  
- Scales numerical features  
- Automates preprocessing steps  

---

## 🧠 Problem Statement
Real-world datasets are often incomplete, inconsistent, and not directly suitable for machine learning models.  
This project addresses this challenge by building a structured pipeline that standardizes and automates data preparation.

---

## 🔄 Workflow

Raw Data → Data Cleaning → Feature Transformation → Pipeline → Processed Data


---

## ⚙️ Implementation

### 🔹 Data Loading
- Loaded dataset using Pandas  
- Inspected structure using `.head()`, `.info()`  

---

### 🔹 Data Cleaning
- Removed unnecessary columns (`customerID`)  
- Converted `TotalCharges` to numeric  
- Handled missing values using median  

---

### 🔹 Feature Engineering
- Converted categorical variables into numerical format  
- Encoded target variable (Churn → 0/1)  

---

### 🔹 Data Transformation
- Applied **StandardScaler** for numerical features  
- Applied **OneHotEncoder** for categorical features  

---

### 🔹 Pipeline Creation
- Built preprocessing pipelines using Scikit-learn  
- Combined using **ColumnTransformer**  
- Automated full preprocessing workflow  

---

### 🔹 Pipeline Execution
- Fitted pipeline on training data  
- Transformed training and testing datasets  

---

### 🔹 Saving Pipeline
- Saved pipeline using Joblib  
- Enables reuse for future predictions  

---

## 📊 Output

- ✔ Cleaned dataset  
- ✔ Transformed dataset  
- ✔ Pipeline file (`churn_pipeline.pkl`)  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Joblib  

---

## 📁 Project Structure

Task1_Data_Pipeline/
│── data/
│ └── churn.csv
│
│── notebook/
│ └── data_pipeline.ipynb
│
│── models/
│ └── churn_pipeline.pkl
│
│── outputs/
│ └── transformed_data.csv
│
│── requirements.txt
│── README.md


---

## ▶️ How to Run

1. Clone the repository:
   
    git clone https://github.com/JayaLakshmi-Y23IT008/codtech-data-science-internship.git

3. Navigate to the project:
   
   cd codtech-data-science-internship/Task1_Data_Pipeline

4. Install dependencies:

   pip install -r requirements.txt

4. Run the notebook:

   jupyter notebook notebook/data_pipeline.ipynb


5. Execute all cells to generate outputs.

---

## 🎓 Key Learning

- Data cleaning and preprocessing techniques  
- Handling missing and inconsistent data  
- Feature transformation and encoding  
- Building reusable pipelines  
- Preparing data for machine learning  

---

## 🏁 Conclusion
This project highlights the importance of data preprocessing in the data science workflow.  
A well-designed pipeline improves efficiency, ensures consistency, and simplifies future model development.

---

## 👩‍💻 Author
JayaLakshmi Bakka
