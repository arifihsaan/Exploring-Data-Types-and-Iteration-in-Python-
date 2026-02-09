# Exploring Python Data Types and Data Manipulation using the Titanic Dataset

## Project Overview
This project demonstrates the application of intermediate Python data types,
iteration, and lambda functions in the context of data exploration and
preprocessing. Using the Titanic dataset, this notebook focuses on understanding
feature characteristics and applying efficient data manipulation techniques
commonly used in data science workflows.

The project emphasizes clarity, efficiency, and reasoning behind each
transformation rather than model building.

---

## Objectives
- Identify and classify data types within a dataset
- Distinguish between ordinal and nominal categorical features
- Apply looping structures for efficient data exploration
- Use lambda functions for feature transformation
- Prepare data for further analysis or modeling

---

## Dataset
- **Name:** Titanic Dataset  
- **Description:** Contains demographic and travel information of Titanic passengers  
- **Target Variable:** `Survived`

---

## Key Topics Covered

### 1. Data Type Identification
- Numerical vs categorical features
- Continuous vs discrete variables
- Understanding feature roles in analysis

### 2. Categorical Feature Classification
Categorical features are classified based on their inherent characteristics:
- **Ordinal:** `Pclass`
- **Nominal:** `Sex`, `Embarked`
- **Binary Nominal:** `Survived`

This classification supports appropriate encoding and analysis decisions.

### 3. Data Exploration Using Iteration
Looping structures are used to efficiently explore multiple features within
the DataFrame, such as inspecting value distributions and summary statistics,
while avoiding repetitive code.

### 4. Data Manipulation with Lambda Functions
Lambda functions are applied for concise feature transformations:
- Numerical transformation: grouping passengers by age
- Categorical transformation: encoding categorical labels into numeric values

These transformations support feature engineering and preprocessing.

---

## Tools & Libraries
- Python
- Pandas
- Jupyter Notebook

---

## Project Structure
