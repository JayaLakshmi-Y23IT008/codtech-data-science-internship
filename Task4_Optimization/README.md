# 📈 Task 4: Optimization Technique Using Python

## 👩‍💻 Internship Details

* **Name:** Bakka Jaya Lakshmi
* **Company:** CODTECH IT Solutions Private Limited
* **Domain:** Data Science
* **Intern ID:** CTIS9743
* **Duration:** 6 Weeks

---

🚀 **Production Optimization System developed using Linear Programming and SciPy to maximize profit under resource constraints.**

---

# 🎯 Project Objective

The objective of this project is to apply mathematical optimization techniques to maximize company profit while satisfying production and resource constraints.

This project demonstrates how optimization methods can support better decision-making in real-world business environments.

---

# 📊 Problem Statement

A manufacturing company produces two products:

* Product A
* Product B

Each product generates a specific profit and consumes available resources.

The goal is to determine the optimal quantity of each product that should be produced in order to:

✅ Maximize total profit

while satisfying:

✅ Resource limitations

✅ Production constraints

---

# 🔄 Optimization Workflow

```text
Business Problem
        ↓
Define Objective Function
        ↓
Define Constraints
        ↓
Apply Linear Programming
        ↓
Find Optimal Solution
        ↓
Analyze Results
        ↓
Visualize Output
```

---

# ⚙️ Optimization Technique

The project uses:

### Linear Programming (LP)

Linear Programming is a mathematical optimization technique used to maximize or minimize an objective function subject to a set of constraints.

### SciPy Optimization

The optimization problem is solved using:

```python
scipy.optimize.linprog
```

which efficiently finds the optimal solution for linear programming problems.

---

# ⚙️ Implementation Steps

### 🔹 1. Problem Definition

* Defined profit values for Product A and Product B
* Specified optimization objective

---

### 🔹 2. Objective Function Creation

Created a profit maximization function.

Since `linprog()` performs minimization, the profit function was converted appropriately for maximization.

---

### 🔹 3. Constraint Definition

Defined production constraints such as:

* Resource limitations
* Production capacity restrictions

These constraints ensure realistic solutions.

---

### 🔹 4. Optimization Execution

Used SciPy's optimization solver to:

* Process constraints
* Evaluate feasible solutions
* Determine optimal production quantities

---

### 🔹 5. Result Analysis

Obtained:

* Optimal units of Product A
* Optimal units of Product B
* Maximum achievable profit

---

### 🔹 6. Visualization

Generated a graphical representation of optimal production quantities to improve result interpretation.

---

# 📈 Project Outputs

The project generates:

* ✔ Optimal Product Quantities
* ✔ Maximum Profit Value
* ✔ Optimization Results Summary
* ✔ Production Visualization Graph

---

## 📊 Optimization Graph

![Optimization Graph](outputs/optimization_graph.png)

---

# 🛠️ Technologies Used

* Python
* NumPy
* SciPy
* Matplotlib
* Jupyter Notebook

---

# 📁 Project Structure

```text
Task4_Optimization/
│
├── notebook/
│   └── optimization_project.ipynb
│
├── outputs/
│   └── optimization_graph.png
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
cd codtech-data-science-internship/Task4_Optimization
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook notebook/optimization_project.ipynb
```

### 5. Execute All Cells

Running all notebook cells will:

* Define optimization problem
* Apply linear programming
* Generate optimal solution
* Calculate maximum profit
* Create visualization graph

---

# 🎓 Key Learning Outcomes

Through this project, I gained practical experience in:

* Mathematical Optimization
* Linear Programming
* Constraint-Based Problem Solving
* Business Decision Modeling
* SciPy Optimization Library
* Data Visualization
* Operations Research Concepts

---

# 🏁 Conclusion

This project demonstrates the practical application of optimization techniques in solving real-world business problems.

By leveraging Linear Programming and SciPy, the system efficiently determines the optimal production strategy that maximizes profit while satisfying operational constraints.

---

## 👩‍💻 Author

**Bakka Jaya Lakshmi**
