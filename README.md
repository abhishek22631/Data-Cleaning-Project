# 🧹 Data Cleaning with Pandas: Handling Missing & Duplicate Values

## 📌 Project Overview
This project demonstrates essential **data preprocessing techniques** using **Python and Pandas**, focusing on:

- Handling **missing values**
- Detecting and removing **duplicate records**

Data cleaning is a critical step in data analysis and machine learning pipelines, and this project showcases common, practical approaches used in real-world datasets.

---

## 📊 Datasets Used

### 1️⃣ `clv_data.csv`
- Used in **Handling Missing Values.ipynb**
- Contains customer-related data such as:
  - Age
  - Days on platform
  - Other customer attributes
- Includes **missing values**, making it suitable for demonstrating data imputation and deletion techniques

### 2️⃣ Duplicate Values Dataset
- Used in **Handling duplicate values.ipynb**
- **Manually created inside the notebook**
- Intentionally includes duplicate rows for demonstration purposes
- No external CSV file is required for this notebook

---

## 📓 Notebook Descriptions

### 🔹 Handling Missing Values.ipynb
This notebook focuses on identifying and handling missing data.

**Key operations:**
- Inspecting dataset structure using `df.info()`
- Identifying missing values with `isnull().sum()`
- Handling missing values by:
  - **Mean imputation** for numerical columns
  - **Dropping rows** with missing values
- Checking for duplicate rows after cleaning

**Techniques demonstrated:**
- Data inspection  
- Mean-based imputation  
- Row-wise deletion  
- Duplicate detection  

---

### 🔹 Handling duplicate values.ipynb
This notebook demonstrates how to work with duplicate data.

**Key operations:**
- Creating a sample dataset with duplicate rows
- Identifying duplicates using `df.duplicated()`
- Removing duplicates using `drop_duplicates()`

**Techniques demonstrated:**
- Duplicate row detection  
- Dataset de-duplication  

---

## 🛠️ Technologies Used
- **Python 3**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/data-cleaning-pandas.git

2. Navigate to the project directory:
   ```bash
   cd data-cleaning-pandas

3. Open Jupyter Notebook:
   ```bash
   jupyter notebook

4. Run the notebooks:

- Handling Missing Values.ipynb
- Handling duplicate values.ipynb

# 📈 Learning Outcomes
By completing this project, one will learn how to:

- Inspect datasets for quality issues
- Handle missing values using different strategies
- Identify and remove duplicate records
- Apply Pandas functions commonly used in real-world data cleaning

# 📌Author
**Abhishek Chakraborty** - Aspiring Data Analyst | Power BI | SQL | Excel

- 📧 Email: abhishekchakraborty22@yahoo.com
- 🔗 GitHub: https://github.com/abhishek22631
