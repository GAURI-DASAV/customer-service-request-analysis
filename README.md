# Customer Service Request Analysis

## Project Overview

This project focuses on analyzing customer service request (311) data to understand complaint patterns, perform data cleaning, visualize trends, and apply statistical analysis. The analysis helps identify major complaint types, response times, and differences across cities.

---

## Objectives

* To assess and clean the dataset for analysis
* To perform exploratory data analysis (EDA)
* To visualize complaint patterns using graphs
* To calculate request closing time
* To identify significant variables using statistical testing
* To perform Kruskal-Wallis test for hypothesis testing

---

## Dataset Description

The dataset contains information about customer service requests, including:

* Unique Key
* Created Date
* Closed Date
* Complaint Type
* City
* Agency
* Status
* Location
* Latitude and Longitude

The data represents service request calls made by customers.

---

## Tools and Technologies Used

### Programming Language

* Python

### Libraries

* Pandas – Data manipulation and analysis
* NumPy – Numerical operations
* Matplotlib – Data visualization
* Seaborn – Statistical visualization
* SciPy – Statistical analysis

---

## Tasks Performed

### 1. Data Understanding

* Imported dataset using Pandas
* Displayed dataset structure
* Checked column names
* Identified dataset shape
* Detected missing values

### 2. Data Cleaning

* Removed records with missing Closed Date
* Ensured correct timeline between Created Date and Closed Date
* Calculated Request Closing Time
* Converted time into seconds
* Replaced missing City values with "Unknown City"

### 3. Exploratory Data Analysis (EDA)

* Created frequency plots
* Generated bar charts for complaint types
* Identified top 10 complaint types
* Visualized complaints across cities

### 4. Data Visualization

* Bar charts
* Scatter plots
* Hexbin plots
* Multi-category comparison charts

### 5. Statistical Analysis

* Calculated average response time
* Performed Kruskal-Wallis test
* Evaluated p-value
* Tested hypothesis

---

## Key Results

* Identified the most common complaint types
* Observed variation in complaints across cities
* Calculated response time for service requests
* Determined whether response times differ significantly between complaint types

---

## Conclusion

The project demonstrates the importance of data cleaning, visualization, and statistical testing in analyzing customer service requests. The analysis helps organizations understand complaint trends and improve service efficiency through data-driven decisions.

---

## How to Run the Project

1. Install required libraries:

pip install pandas numpy matplotlib seaborn scipy

2. Open the Jupyter Notebook:

Govinda.ipynb

3. Run all cells to reproduce results.

---

## Project Files

* Govinda.ipynb – Python notebook containing analysis
* README.md – Project documentation

---

## Author

Name: **Gauri Sandesh Dasav**
Project: Customer Service Request Analysis
Technology: Python Data Analysis
