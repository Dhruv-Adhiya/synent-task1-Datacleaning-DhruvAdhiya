# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

## 📌 Problem Statement

Raw datasets often contain:
- Missing values
- Duplicate records
- Incorrect data types
- Unclear column names

These problems can affect data analysis and machine learning results.

The objective of this project is to clean and preprocess the Titanic dataset and prepare it for further analysis.

---

## 📂 Dataset Details

**Dataset Used:** Titanic Dataset (`Titanic-Dataset.csv`)

The dataset contains passenger information such as:
- Passenger ID
- Name
- Age
- Gender
- Ticket Fare
- Cabin Details
- Survival Status

---

## ⚙️ Approach

The following preprocessing steps were performed using Python and Pandas:

### 1. Handle Missing Values
- Filled missing values in the `Cabin` column with `"Unknown"`
- Filled missing values in the `Fare` column using median values

### 2. Remove Duplicates
- Checked for duplicate rows
- Removed duplicate records from the dataset

### 3. Convert Data Types
- Converted columns into appropriate data types where necessary

### 4. Rename Columns
- Renamed column names for better readability and consistency

### 5. Save Cleaned Dataset
- Exported the cleaned dataset into a new CSV file

---

## 📊 Results

After preprocessing:
- Missing values were handled successfully
- Duplicate records were removed
- Dataset became cleaner and more organized
- Final cleaned dataset was generated

**Output File:** `Titanic_cleaned.csv`

The dataset is now ready for:
- Data Analysis
- Data Visualization
- Machine Learning

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- Jupyter Notebook

## ✅ Output

Clean dataset ready for analysis and preprocessing tasks.
