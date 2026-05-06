
# 📊 Task 1: Data Pipeline Development

🚀 **End-to-end data preprocessing pipeline that converts raw customer churn data into a machine learning-ready format using Scikit-learn.**

---

## 🎯 Why This Project Matters
In real-world applications, raw data is often incomplete, inconsistent, and not suitable for machine learning models.  
This project solves that problem by building an automated pipeline that ensures clean, structured, and reusable data processing.

---

## 🎯 Objective
To design a reusable pipeline that:
- Cleans raw data  
- Handles missing values  
- Encodes categorical features  
- Scales numerical features  
- Automates preprocessing  

---

## 🧠 Why This Project?
In real-world scenarios, data is often messy and cannot be directly used for machine learning models.  
This project solves that problem by creating a structured and automated preprocessing workflow.

---

## 🔄 Workflow


Raw Data
↓
Data Cleaning
↓
Feature Transformation
↓
Pipeline Creation
↓
Processed Data


---

## ⚙️ Implementation Steps

### 🔹 1. Data Loading
- Loaded dataset using Pandas  
- Inspected structure and data types  

---

### 🔹 2. Data Cleaning
- Removed unnecessary column (`customerID`)  
- Converted `TotalCharges` to numeric  
- Handled missing values using median  

---

### 🔹 3. Feature Engineering
- Converted categorical variables into numerical format  
- Encoded target variable (Churn → 0/1)  

---

### 🔹 4. Data Transformation
- Applied **StandardScaler** for numerical features  
- Applied **OneHotEncoder** for categorical features  

---

### 🔹 5. Pipeline Creation
- Built preprocessing pipelines using Scikit-learn  
- Combined transformations using ColumnTransformer  
- Automated entire preprocessing workflow  

---

### 🔹 6. Pipeline Execution
- Fitted pipeline on training data  
- Transformed training and testing datasets  

---

### 🔹 7. Saving Pipeline
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


2. Navigate to the folder:

   cd codtech-data-science-internship/Task1_Data_Pipeline


3. Install dependencies:

   pip install -r requirements.txt


4. Run the notebook:

   jupyter notebook notebook/data_pipeline.ipynb


5. Execute all cells to generate results.

---

## 🎓 Key Learning

- Data preprocessing techniques  
- Handling real-world datasets  
- Feature transformation and encoding  
- Building reusable pipelines  
- Preparing data for machine learning  

---

## 🏁 Conclusion
This project highlights the importance of preprocessing in data science workflows.  
A well-designed pipeline improves efficiency, ensures consistency, and simplifies future model development.

---

## 👩‍💻 Author
JayaLakshmi Bakka
