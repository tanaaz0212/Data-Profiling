# Data-Profiling
#  Data Profiler Project

##  Project Overview

This project focuses on **data collection, preprocessing, merging, and analysis** using multiple data sources such as CSV, JSON, SQL, and API data.
The goal is to clean and transform raw data into a structured dataset for analysis and visualization.

---

##  Objective

* Load data from multiple sources (CSV, JSON, SQL, API)
* Merge datasets into a single dataframe
* Perform data cleaning and preprocessing
* Conduct exploratory data analysis (EDA)
* Generate insights and create visualizations
* Save final cleaned dataset

---

##  Project Files

| File Name                  | Description                         |
| -------------------------- | ----------------------------------- |
| `main.ipynb`               | Jupyter Notebook with complete code |
| `customer_data.csv`        | Main dataset                        |
| `customer_data.json`       | JSON version of dataset             |
| `database.db`              | SQL database file                   |
| `cleaned_data.csv`         | Final processed dataset             |
| `data_profile_report.html` | Data profiling report               |

---

##  Data Sources

### 1. CSV File

* Contains customer details such as age, gender, income, etc.

### 2. JSON File

* Same or additional structured customer data

### 3. SQL Database

* Contains customer income table (`customer_income`)

### 4. API Data (Simulated)

* Economic indicators:

  * Inflation rate
  * GDP growth

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQLite3
* JSON

---

##  Project Workflow

### Step 1: Data Loading

* Load CSV using `pandas.read_csv()`
* Load JSON using `json.load()`
* Load SQL using `sqlite3` and `read_sql()`
* Load API (dummy data using NumPy)

---

### Step 2: Data Merging

* Merge all datasets using `merge()` on `customer_id`

---

### Step 3: Data Cleaning

* Handle missing values using forward fill
* Remove duplicate records

---

### Step 4: Exploratory Data Analysis (EDA)

* Age distribution (Histogram)
* Income vs churn (Boxplot)
* Correlation heatmap

---

### Step 5: Feature Engineering

* Created new column:

  * `total_spent = purchase_count * avg_purchase_value`

---

### Step 6: Save Final Data

* Export cleaned dataset as `cleaned_data.csv`

---

##  Output

* Cleaned dataset ready for analysis
* Visual insights from EDA
* Optional HTML profiling report

---

##  How to Run

1. Open Jupyter Notebook
2. Run all cells step by step
3. Ensure all dataset files are in correct path
4. Final output will be saved automatically

---

##  Important Notes

* Make sure all file paths are correct
* Install required libraries before running:

```bash
pip install pandas numpy matplotlib seaborn
```

---

##  Conclusion

This project demonstrates how to:

* Work with multiple data sources
* Clean and preprocess real-world data
* Perform basic data analysis and visualization


---
