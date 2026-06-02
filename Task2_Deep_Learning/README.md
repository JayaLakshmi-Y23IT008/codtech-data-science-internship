# 🤖 Task 2: Deep Learning Model for Classification

## 👩‍💻 Internship Details

* **Name:** Bakka Jaya Lakshmi
* **Company:** CODTECH IT Solutions Private Limited
* **Domain:** Data Science
* **Intern ID:** CTIS9743
* **Duration:** 6 Weeks

---

🚀 **Deep learning classification model built using TensorFlow and Keras to classify breast cancer tumors as malignant or benign.**

---

# 🎯 Objective

The objective of this project is to build, train, and evaluate an Artificial Neural Network (ANN) capable of performing binary classification using deep learning techniques.

This project demonstrates how deep learning can be applied to medical datasets to assist in predictive analysis and classification tasks.

---

# 📊 Dataset

The project uses the **Breast Cancer Wisconsin Dataset** available in Scikit-learn.

### Dataset Information

* **Total Samples:** 569
* **Features:** 30
* **Target Classes:** 2
* **Classification Type:** Binary Classification

### Target Labels

| Value | Meaning   |
| ----- | --------- |
| 0     | Malignant |
| 1     | Benign    |

---

# 🔄 Project Workflow

```text
Dataset Loading
        ↓
Data Preprocessing
        ↓
Train-Test Split
        ↓
Feature Scaling
        ↓
Neural Network Creation
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Prediction Generation
        ↓
Model Saving
```

---

# ⚙️ Steps Performed

### 🔹 1. Dataset Loading

* Loaded Breast Cancer Dataset from Scikit-learn
* Converted dataset into a Pandas DataFrame
* Added target labels

---

### 🔹 2. Data Exploration

* Inspected dataset dimensions
* Examined feature names
* Checked dataset structure

---

### 🔹 3. Data Preprocessing

* Split features and target variable
* Applied train-test split
* Prepared data for model training

---

### 🔹 4. Feature Scaling

* Applied StandardScaler
* Normalized feature values
* Improved model convergence and performance

---

### 🔹 5. Neural Network Development

Built an Artificial Neural Network using TensorFlow and Keras.

### Architecture

* Input Layer
* Dense Hidden Layer (16 Neurons, ReLU)
* Dense Hidden Layer (8 Neurons, ReLU)
* Output Layer (1 Neuron, Sigmoid)

---

### 🔹 6. Model Training

* Compiled model using Adam optimizer
* Used Binary Crossentropy loss function
* Trained model for multiple epochs

---

### 🔹 7. Model Evaluation

* Calculated classification accuracy
* Evaluated performance on test data
* Generated predictions

---

### 🔹 8. Model Saving

* Saved trained model as:

```text
deep_learning_model.h5
```

* Allows future predictions without retraining

---

# 📈 Output

The project generates:

* ✔ Classification Accuracy
* ✔ Model Predictions
* ✔ Accuracy Visualization Graph
* ✔ Saved Deep Learning Model (`deep_learning_model.h5`)

---

## 📊 Accuracy Graph

![Accuracy Graph](outputs/accuracy_graph.png)

---

# 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

# 📁 Project Structure

```text
Task2_Deep_Learning/
│
├── notebook/
│   └── deep_learning_model.ipynb
│
├── models/
│   └── deep_learning_model.h5
│
├── outputs/
│   └── accuracy_graph.png
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
cd codtech-data-science-internship/Task2_Deep_Learning
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook notebook/deep_learning_model.ipynb
```

### 5. Execute All Cells

Running all notebook cells will:

* Train the neural network
* Generate predictions
* Create accuracy graph
* Save trained model

---

# 🎓 Key Learning Outcomes

Through this project, I learned:

* Deep Learning Fundamentals
* Artificial Neural Networks (ANN)
* Data Preprocessing Techniques
* Feature Scaling
* Model Training and Evaluation
* TensorFlow and Keras Frameworks
* Model Persistence and Reusability

---

# 🏁 Conclusion

This project demonstrates the implementation of a deep learning classification model using TensorFlow and Keras.

The developed neural network successfully classifies breast cancer tumors with high accuracy and showcases the practical application of deep learning techniques in predictive analytics.

---

## 👩‍💻 Author

**Bakka Jaya Lakshmi**
