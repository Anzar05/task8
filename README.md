# Task 8: Data Cleaning Challenge

## 📌 Objective
The goal of this project is to clean a messy dataset by handling missing values, fixing data types, and treating outliers.

## 📂 Dataset
Titanic Dataset from Kaggle:
https://www.kaggle.com/datasets/yasserh/titanic-dataset

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 🧹 Data Cleaning Steps

### 1. Handling Missing Values
- Filled missing values in Age with mean
- Filled missing values in Embarked with mode
- Dropped Cabin column due to excessive missing values

### 2. Data Type Conversion
- Converted Fare to float
- Converted Survived to category

### 3. Outlier Detection
- Used Boxplot visualization
- Used IQR method to detect outliers

### 4. Outlier Treatment
- Capped outliers using IQR limits

### 5. Removing Duplicates
- Removed duplicate rows

### 6. Saving Cleaned Data
- Exported cleaned dataset as CSV file

## 📊 Output
Cleaned dataset saved as:
cleaned_titanic.csv

## ▶️ How to Run
1. Download dataset from Kaggle
2. Place CSV file in project folder
3. Run Jupyter Notebook

## 📁 Project Structure
Task8/
│── data_cleaning_task8.ipynb
│── Titanic-Dataset.csv
│── cleaned_titanic.csv
│── README.md

## ✅ Result
Successfully cleaned the dataset by handling null values, converting data types, and treating outliers.
