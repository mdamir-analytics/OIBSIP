# ☕ Cafe Sales Data Cleaning

A professional data cleaning project that transforms a messy cafe sales dataset into a clean, analysis-ready dataset using **Python** and **Pandas**. The project demonstrates industry-standard data preprocessing techniques, including missing value handling, data type correction, standardization, outlier detection, and data quality assessment.

---

## 📌 Project Objective

The objective of this project is to identify and resolve common data quality issues in a real-world transactional dataset. The cleaned dataset is prepared for further analysis, visualization, and machine learning applications.

---

## 📂 Dataset Information

- **Dataset:** Dirty Cafe Sales Dataset
- **Rows:** 10,000
- **Columns:** 8
- **File Format:** CSV

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📋 Data Cleaning Workflow

### 1. Data Quality Assessment
- Loaded the dataset
- Examined dataset structure
- Identified missing values
- Checked duplicate records
- Inspected data types
- Generated summary statistics

### 2. Missing Value Handling
- Filled numerical columns using median values
- Filled categorical columns using mode or "Unknown"
- Recalculated missing Total Spent values
- Filled missing transaction dates

### 3. Duplicate Check
- Verified duplicate records
- Confirmed no duplicate rows were present

### 4. Data Standardization
- Removed inconsistent formatting
- Verified unique values

### 5. Data Type Correction
- Converted Quantity to numeric
- Converted Price Per Unit to numeric
- Converted Total Spent to numeric
- Converted Transaction Date to datetime

### 6. Outlier Detection
- Used the IQR method
- Visualized distributions using boxplots
- Evaluated detected outliers
- Retained valid business transactions

### 7. Before vs After Comparison
- Compared missing values
- Compared duplicate records
- Compared data types
- Verified dataset quality

### 8. Export Clean Dataset
- Saved the cleaned dataset as a new CSV file

---

## 📊 Project Results

| Metric | Before | After |
|---------|--------|-------|
| Rows | 10,000 | 10,000 |
| Columns | 8 | 8 |
| Missing Values | 6,826 | 0 |
| Duplicate Rows | 0 | 0 |

---

## 📁 Project Structure

```
Cafe_Sales_Data_Cleaning/
│
├── data/
│   ├── dirty_cafe_sales.csv
│   └── cleaned_cafe_sales.csv
│
├── notebook/
│   └── Cafe-Sales-Data-Cleaning.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone <repository-url>
```

2. Navigate to the project directory

```bash
cd Cafe_Sales_Data_Cleaning
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open **Cafe-Sales-Data-Cleaning.ipynb** and run all cells.

---

## 📈 Skills Demonstrated

- Data Cleaning
- Data Quality Assessment
- Missing Value Imputation
- Data Type Conversion
- Data Standardization
- Outlier Detection
- Exploratory Data Analysis
- Data Preprocessing
- Python Programming
- Pandas
- NumPy
- Matplotlib

---

## 👨‍💻 Author

**MD AMIR**
