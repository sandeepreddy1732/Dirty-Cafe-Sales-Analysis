# Dirty Cafe Sales Analysis

## Project Overview

This project focuses on cleaning and analyzing dirty cafe sales data using Python and SQL.

The dataset contains sales transaction details with missing values, invalid entries, and inconsistent data. The main objective is to clean the raw data, transform it into a structured format, and store the cleaned data in MySQL for further analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- MySQL
- SQLAlchemy
- Jupyter Notebook

## Dataset Information

The dataset contains the following columns:

- Transaction ID
- Item
- Quantity
- Price Per Unit
- Total Spent
- Payment Method
- Location
- Transaction Date

## Project Workflow

### 1. Data Loading
- Imported the raw cafe sales dataset using Pandas.
- Explored the dataset structure and data types.

### 2. Data Exploration
- Checked missing values.
- Identified duplicate records.
- Analyzed column data types.
- Calculated missing value percentages.

### 3. Data Cleaning
- Handled missing values.
- Converted numeric columns into appropriate data types.
- Removed invalid records.
- Handled inconsistent values.
- Converted transaction dates into datetime format.

### 4. Data Transformation
- Prepared the cleaned dataset for database storage.
- Ensured columns had appropriate data types.

### 5. Data Loading into MySQL
- Connected Python to MySQL using SQLAlchemy.
- Loaded the cleaned dataset into a MySQL table named `retail_sales`.

### 6. SQL Analysis
- Used SQL queries to analyze sales data.
- Performed aggregations and grouped analysis.
- Identified top-performing items based on sales quantities.

## Project Files

- `Dirty_Cafe_Sales_Analysis.html` – Exported Jupyter Notebook containing the project code and outputs.
- `Dirty_Cafe_Sales_Analysis.ipynb` – Original Jupyter Notebook (if included).

## How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/sandeepreddy1732/Dirty-Cafe-Sales-Analysis.git
   ```

2. Install the required libraries:

   ```bash
   pip install pandas numpy sqlalchemy mysql-connector-python jupyter
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Configure your MySQL connection using your own database credentials.

5. Run the notebook cells.

## Key Learnings

- Real-world data cleaning and preprocessing.
- Handling missing and inconsistent data.
- Data type conversion and validation.
- Integrating Python with MySQL.
- Performing SQL-based data analysis.

## Author

**Sandeep Reddy**

GitHub: [sandeepreddy1732](https://github.com/sandeepreddy1732)
