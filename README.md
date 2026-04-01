
# DevelopersHub Corporation - Data Science & Analytics Internship

 I am **Ahmad Ammar**, a Data Science Intern at DevelopersHub. This repository is a documentation of the tasks I completed during my internship. My work involved data cleaning, visualization, and building predictive models using Python.

---

## 🛠️ Tech Stack & Tools
I used a variety of industry-standard tools to process data and build machine learning models:

| Tool | Purpose |
| :--- | :--- |
| **Python 3.x** | Core programming language |
| **Pandas** | Data manipulation (handling .csv and .xlsx files) |
| **Seaborn** | Loading the Iris dataset and statistical visualization |
| **Matplotlib** | Plotting graphs and customized charts |
| **Scikit-Learn** | Data scaling, encoding, and ML modeling |
| **Jupyter Notebook** | Environment for interactive development |

---

## 📂 Internship Tasks Overview

### 🌸 Task 1: Exploring and Visualizing the Iris Dataset
* **Objective:**
*  To understand flower species distribution through data visualization.
* **Methodology:**
*  * Loaded the dataset **directly from the Seaborn library** (`sns.load_dataset('iris')`).
    * Performed EDA using `.describe()` and `.info()`.
    * Created Scatter Plots and Box Plots to see species clusters.
* **Results & Insights:**
*  * The 'Setosa' species is clearly distinct because its petals are much smaller and don't overlap with other species.
    * **Source:**
    * Built-in Seaborn Dataset.
   
---


### 💳 Task 2: Personal Loan Purchase Prediction
* **Objective:**
*  To predict which customers will accept personal loan offers.
* **Methodology:**
* * Processed the data from an **Excel (.xlsx) file**.
    * Cleaned missing values and visualized the relationship between income and loan acceptance.
    * Trained a **Logistic Regression** model after applying `StandardScaler`.
* **Challenge Overcome:**
*  Initially, the model gave a 'Convergence Warning'. I solved this by scaling the features, which helped the model learn better and faster.
* **Results & Insights:**
*  Annual Income is the biggest factor in loan prediction.

---
### 🏦 Task 3: Customer Churn Prediction
* **Objective:**
*  To identify bank customers likely to close their accounts.
* **Methodology:**
* * Used the **Churn_Modelling.csv** dataset.
    * Handled categorical data (Gender, Geography) using **Label Encoding**.
    * Analyzed Feature Importance to see what drives customer behavior.
* **Results & Insights:**
*  The model achieved **81% accuracy**. Older customers and less active members were found more likely to churn, helping the bank target these specific groups.

---

## 💡 Key Takeaways from the Internship
Throughout this experience at DevelopersHub, I have learned:
1.  **Data Cleaning is Key:**
2.   Real-world data is often messy, and cleaning it (handling missing values, dropping IDs) is 70% of the work.
3.  **Visualization Speaks:**
4.  A simple Scatter plot can reveal patterns that raw numbers cannot.
5.  **Model Tuning:**
6.   Learned how to fix common errors like Convergence Warnings and how to interpret model coefficients.

---

## 👤 My_Self
**Name:** Ahmad Ammar  
**Role:** Data Science Intern  
**Organization:** DevelopersHub Corporation



