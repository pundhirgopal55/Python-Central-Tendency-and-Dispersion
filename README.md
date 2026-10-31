# Python – Central Tendency and Dispersion

## 📌 Project Overview

This project focuses on understanding and implementing the concepts of **Central Tendency and Dispersion** using Python. It uses the Pandas and NumPy libraries to perform statistical analysis on the Diabetes dataset.

The notebook demonstrates how to calculate different statistical measures, analyze numerical columns, and understand the distribution and spread of data.

## 🎯 Objectives

- Understand the concepts of Central Tendency and Dispersion.
- Calculate Mean, Median, and Mode.
- Calculate Variance and Standard Deviation.
- Find Quartiles and Interquartile Range (IQR).
- Calculate the Range of numerical data.
- Understand Upper and Lower Boundaries for outlier detection.
- Perform statistical analysis on individual dataset columns.

## 📚 Topics Covered

### 1. Data Loading and Inspection
- Importing Python libraries.
- Loading the Diabetes dataset using Pandas.
- Checking the number of rows and columns.
- Displaying column names and data types.
- Viewing the first 10 records.
- Selecting numerical columns using NumPy and Pandas.

### 2. Measures of Central Tendency

Central Tendency represents the center or typical value of a dataset.

- **Mean:** Average of all observations.
- **Median:** Middle value of the dataset after sorting.
- **Mode:** Most frequently occurring value.

These measures are calculated for all numerical columns and selected individual columns.

### 3. Measures of Dispersion

Dispersion describes how spread out the values are in a dataset.

- **Variance:** Measures the spread of data around the mean.
- **Standard Deviation:** Measures the average spread of values around the mean.
- **Quartiles:** Divide the dataset into four equal parts.
- **IQR (Interquartile Range):** Difference between the third quartile (Q3) and first quartile (Q1).
- **Range:** Difference between the maximum and minimum values.

### 4. Outlier Detection

The notebook also covers the concept of outlier detection using the IQR method.

- Upper Boundary
- Lower Boundary
- Understanding unusual values in numerical data.

### 5. Column-wise Statistical Analysis

Individual statistical analysis is performed on the following columns:

- Glucose
- BloodPressure
- Pregnancies
- SkinThickness
- Insulin
- BMI
- Age

For these columns, Mean, Median, and Mode are calculated. Minimum and Maximum values are also checked for Glucose.

## 🛠️ Technologies and Libraries Used

- **Python** – Programming language.
- **NumPy** – Numerical calculations.
- **Pandas** – Data loading and statistical analysis.
- **Matplotlib** – Data visualization library.

## 📂 Project Structure

```text
Python-Central-Tendency-and-Dispersion/
│
├── Central_Tendency_Dispersion.ipynb
├── diabetes.csv
└── README.md
```

## ▶️ How to Run This Project

1. Clone this repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Open the project folder.

3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib
   ```

4. Make sure the `diabetes.csv` dataset is available in the correct location.

5. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `Central_Tendency_Dispersion.ipynb` and run the cells.

## 📖 Learning Outcomes

After completing this notebook, I learned:

- How to perform statistical analysis using Python.
- How to calculate measures of Central Tendency.
- How to understand the spread and distribution of data.
- How to work with numerical columns using Pandas.
- How to calculate IQR and understand outlier boundaries.
- How to analyze individual columns of a dataset.

## 👨‍💻 Author

**Gopal Pundhir**

This project is part of my Python and Data Science learning journey.

