# 📊 Task 1: Data Pipeline Development

## 🔹 Overview
This task focuses on building an automated data preprocessing pipeline for customer churn data. The objective is to convert raw, unstructured data into a clean and machine learning-ready format using Python libraries such as Pandas and Scikit-learn.

---

## 🔹 Objective
To design and implement a complete data pipeline that performs:
- Data loading
- Data cleaning
- Data transformation
- Feature engineering
- Pipeline automation

---

## 🔹 Dataset Description
The dataset used is the **Customer Churn Dataset**, which contains customer information such as demographics, services, and account details.

### Key Features:
- Customer demographics (gender, senior citizen, etc.)
- Account information (tenure, charges)
- Service details (internet, phone services)
- Target variable: **Churn (Yes/No)**

---

## 🔹 Workflow

The pipeline follows a structured workflow:

Raw Data → Data Cleaning → Feature Transformation → Pipeline → Processed Data


---

## 🔹 Implementation Steps

### 1. Data Loading
- Dataset is loaded using Pandas
- Data is inspected using `.head()`, `.info()`, and `.shape()`

---

### 2. Data Cleaning
- Removed unnecessary columns (e.g., customerID)
- Handled missing values in `TotalCharges`
- Converted data types to appropriate formats

---

### 3. Feature Engineering
- Converted categorical variables into numerical format
- Encoded target variable (Churn → 0/1)

---

### 4. Data Transformation
- Numerical features scaled using **StandardScaler**
- Categorical features encoded using **OneHotEncoder**

---

### 5. Pipeline Creation
- Built separate pipelines for numerical and categorical data
- Combined them using **ColumnTransformer**
- Automated preprocessing steps using **Pipeline**

---

### 6. Applying the Pipeline
- Fitted pipeline on training data
- Transformed both training and testing datasets

---

### 7. Saving the Pipeline
- Saved the trained preprocessing pipeline using **Joblib**
- Enables reuse in future tasks or deployment

---

## 🔹 Output

- Cleaned and transformed dataset
- Saved pipeline file: `churn_pipeline.pkl`
- Structured data ready for machine learning models

---

## 🔹 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

## 🔹 Project Structure

Task1_Data_Pipeline/
│
├── data/
│   └── churn.csv
│
├── notebook/
│   └── data_pipeline.ipynb
│
├── models/
│   └── churn_pipeline.pkl
│
├── outputs/
│   └── transformed_data.csv
│
├── requirements.txt
│
└── README.md


---



## 🔹 How to Run the Project

Follow these steps to execute the data pipeline:

---

### 1️⃣ Clone the Repository

Open terminal / command prompt and run:

git clone https://github.com/JayaLakshmi-Y23IT008/codtech-data-science-internship.git

---

### 2️⃣ Navigate to Task 1 Folder

cd codtech-data-science-internship/Task1_Data_Pipeline

---

### 3️⃣ Install Required Libraries

Make sure Python is installed, then run:

pip install -r requirements.txt

---

### 4️⃣ Open Jupyter Notebook

Start Jupyter Notebook:

jupyter notebook

---

### 5️⃣ Run the Notebook

- Open: notebook/data_pipeline.ipynb  
- Click: **Run All Cells**

---

### 6️⃣ Output

After execution, you will get:

- Cleaned and transformed dataset  
- Saved pipeline file (`churn_pipeline.pkl`)  
- Optional output file (`transformed_data.csv`)

---

## 🔹 Notes

- Ensure all files are in correct folders  
- Dataset should be inside the `data/` folder  
- No manual preprocessing needed (pipeline handles everything)

