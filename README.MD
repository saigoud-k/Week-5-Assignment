  
### Week 5 – Matplotlib 

**Student Name:** Sai Goud Koyyala  
**Course:** Data Analytics  
**Instructor:** John Koenig  

---

## Project Overview

This project analyzes a medical laboratory dataset using Python and Matplotlib.  

The objective is to explore patterns, distributions, and trends within the dataset while strictly using Matplotlib.

All visualizations were created using:
- `plt.figure()`
- `plt.bar()`
- `plt.hist()`
- `plt.plot()`

---

## Dataset Description

The dataset contains medical laboratory test records, including:

- Test Name  
- Date Collected  
- Numeric Result  
- Units  
- Provider Organization  
- Abnormal Value Indicator  

The dataset includes thousands of lab test records across multiple years.

---

## Questions Explored

1. What are the most frequently performed lab tests?
2. How are numeric test results distributed?
3. How have average numeric test results changed over time?

---

## Visualizations Created

### 1️⃣ Top 10 Most Common Lab Tests
A bar chart identifying the most frequently performed laboratory tests.

**Insight:**  
A small group of tests accounts for a large portion of total testing volume, indicating concentrated demand in specific diagnostic areas.

---

### 2️⃣ Distribution of Numeric Test Results
A histogram showing the spread and variability of numeric lab results.

**Insight:**  
Numeric results show significant variation, reflecting differences across test types and patient measurements.

---

### 3️⃣ Average Numeric Test Results Over Time
A line chart displaying yearly changes in average numeric test results.

**Insight:**  
Average values fluctuate year-to-year, indicating variability in testing patterns and patient data across time.

---

## Tools Used

- Python
- Pandas (data cleaning and aggregation)
- Matplotlib (stateless interface)
- Jupyter Notebook

---

## Key Takeaways

- Lab testing volume is concentrated in specific test categories.
- Numeric test results vary widely across records.
- Yearly trends show fluctuation rather than a consistent increase or decrease.

This project demonstrates data cleaning, aggregation, and visualization using Matplotlib’s stateless plotting interface.

---

## How to Run

1. Install required libraries: