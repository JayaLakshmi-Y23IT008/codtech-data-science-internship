# 🏠 Task 3: End-to-End Data Science Project

## 👩‍💻 Internship Details

* **Name:** Bakka Jaya Lakshmi
* **Company:** CODTECH IT Solutions Private Limited
* **Domain:** Data Science
* **Intern ID:** CTIS9743
* **Duration:** 6 Weeks

---

🚀 **Complete Machine Learning workflow for predicting California housing prices using Scikit-learn, including data preprocessing, model training, evaluation, visualization, and model deployment preparation.**

---

# 🎯 Project Objective

The objective of this project is to develop a complete end-to-end machine learning pipeline capable of predicting house prices based on various housing-related features.

This project demonstrates the complete machine learning lifecycle from data acquisition to model evaluation and deployment readiness.

---

# 📊 Dataset

The project utilizes the **California Housing Dataset** provided by Scikit-learn.

### Dataset Information

* **Total Samples:** 20,640
* **Features:** 8
* **Target Variable:** Median House Value
* **Dataset Type:** Regression

### Features Used

* MedInc (Median Income)
* HouseAge
* AveRooms
* AveBedrms
* Population
* AveOccup
* Latitude
* Longitude

---

# 🔄 Project Workflow

```text
Dataset Loading
        ↓
Data Exploration
        ↓
Data Visualization
        ↓
Data Preprocessing
        ↓
Train-Test Split
        ↓
Feature Scaling
        ↓
Model Training
        ↓
Prediction
        ↓
Model Evaluation
        ↓
Model Saving
```

---

# ⚙️ Steps Performed

### 🔹 1. Dataset Loading

* Loaded California Housing Dataset
* Converted data into Pandas DataFrame
* Added target variable

---

### 🔹 2. Data Exploration

* Inspected dataset structure
* Analyzed feature information
* Checked statistical summaries
* Verified data quality

---

### 🔹 3. Data Visualization

* Visualized housing price distribution
* Explored dataset patterns
* Identified relationships between variables

---

### 🔹 4. Data Preprocessing

* Separated features and target variable
* Prepared data for model training

---

### 🔹 5. Train-Test Split

* Divided dataset into training and testing sets
* Maintained reproducibility using random state

---

### 🔹 6. Feature Scaling

* Applied StandardScaler
* Standardized numerical features
* Improved model performance

---

### 🔹 7. Model Training

* Implemented Linear Regression algorithm
* Trained model on processed training data
* Generated predictive model

---

### 🔹 8. Prediction

* Predicted house prices on unseen test data
* Compared actual and predicted values

---

### 🔹 9. Model Evaluation

Evaluated model performance using:

* Mean Squared Error (MSE)
* R² Score

These metrics help measure prediction accuracy and model effectiveness.

---

### 🔹 10. Model Saving

Saved trained model as:

```text
house_price_model.pkl
```

This allows future predictions without retraining the model.

---

# 📈 Project Outputs

The project generates:

* ✔ Predicted House Prices
* ✔ Mean Squared Error (MSE)
* ✔ R² Score
* ✔ Prediction Visualization Graph
* ✔ Saved Machine Learning Model

---


---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Joblib
* Jupyter Notebook

---

# 📁 Project Structure

```text
Task3_End_to_End_Project/
│
├── notebook/
│   └── house_price_prediction.ipynb
│
├── models/
│   └── house_price_model.pkl
│
├── outputs/
│   └── prediction_graph.png
│
├── requirements.txt
│
└── README.md
```

---

# ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/JayaLakshmi-Y23IT008/codtech-data-science-internship.git
```

### 2. Navigate to Task Folder

```bash
cd codtech-data-science-internship/Task3_End_to_End_Project
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook notebook/house_price_prediction.ipynb
```

### 5. Execute All Cells

Running all notebook cells will:

* Load and preprocess data
* Train the regression model
* Generate predictions
* Evaluate performance
* Save the trained model

---

# 🎓 Key Learning Outcomes

Through this project, I gained practical experience in:

* End-to-End Machine Learning Workflows
* Data Exploration and Analysis
* Feature Scaling Techniques
* Regression Modeling
* Model Evaluation Metrics
* Data Visualization
* Model Persistence using Joblib
* Real-World Predictive Analytics

---

# 🏁 Conclusion

This project demonstrates a complete machine learning pipeline for house price prediction.

By integrating data preprocessing, model training, evaluation, visualization, and model saving, the project showcases essential skills required for real-world data science applications.

---

## 👩‍💻 Author

**Bakka Jaya Lakshmi**
