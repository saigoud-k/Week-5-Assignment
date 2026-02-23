# Week 5 – Matplotlib Data Visualization Project

## Student
Sai Goud Koyyala

## Project Overview

This project analyzes a lab results dataset using Python and Matplotlib.

The objective was to create three professional data visualizations that explore trends, distributions, and categorical relationships within the dataset.

All visualizations were created using Matplotlib and follow best practices including:

- Clear titles
- Labeled axes with units
- Horizontal stacked bar charts for better readability
- Sorted categories for improved interpretation
- Clean and stateless code execution

---

## Dataset

File used:
Lab Results.csv

Key columns:
- Date_Collected
- Numeric_Result
- Test_Name

Data preprocessing steps:
- Converted date column to datetime
- Converted numeric results to numeric format
- Removed missing values
- Created a Year column for trend analysis
- Categorized numeric results into Low, Normal, High

---

## Visualizations

### 1. Average Lab Result by Year
A line chart showing the yearly average of lab values.

Purpose:
- Identify trends over time
- Analyze fluctuations in average test results

---

### 2. Test Type by Result Category
The bar chart showing distribution of Low, Normal, and High results for each test type.

Purpose:
- Compare result distributions
- Understand test behavior patterns

---

### 3. Lab Test Distribution by Year
The bar chart showing the number of tests performed each year by test type.

Purpose:
- Compare test frequency across years
- Identify changes in testing patterns

---

## How to Run

1. Clone the repository
2. Ensure the dataset file is in the same directory
3. Run the Python script or Jupyter notebook
4. Restart kernel and Run All to verify stateless execution

---

## Tools Used

- Python
- Pandas
- Matplotlib

---

## Project Status

Completed and ready for submission.
