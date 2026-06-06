# 🎓 Student Performance Analysis | Python EDA & Reporting

## 📌 Project Overview

This project analyzes student academic performance data to identify the key factors influencing exam scores, detect at-risk students, and provide actionable recommendations for improving educational outcomes.

Using Python-based Exploratory Data Analysis (EDA), statistical analysis, and data visualization techniques, this project uncovers insights related to parental education, test preparation, gender performance, and subject correlations.

The final deliverable includes a Principal's Report with strategic recommendations for improving student success rates.

---

## 🎯 Business Problem

A school principal wants to understand:

* Which factors have the greatest impact on student performance.
* Whether test preparation courses improve academic outcomes.
* Which student groups are most at risk academically.
* How to improve overall student achievement in the next academic year.

The goal is to transform raw student performance data into actionable educational insights.

---

## 📊 Dataset Information

**Dataset:** Students Performance

**Source:** Kaggle

**Records:** 1,000 Students

**Features:**

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Math Score
* Reading Score
* Writing Score

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Excel
* Google Colab Notebook

---

## 🔍 Project Workflow

### 1. Data Cleaning & Exploration

* Loaded and inspected dataset structure
* Checked data types and missing values
* Created new analytical features:

  * Total Score
  * Average Score
* Generated summary statistics

### 2. Factor Analysis

Investigated five key business questions:

✅ Does parental education affect student performance?

✅ Do students who complete test preparation score higher?

✅ What is the relationship between reading, writing, and math scores?

✅ Which gender performs better in each subject?

✅ How are total scores distributed across students?

### 3. Data Visualization

Created multiple visualizations including:

* Box Plot
* Bar Chart
* Correlation Heatmap
* Grouped Bar Chart
* Histogram
* Scatter Plot

### 4. At-Risk Student Segmentation

Defined at-risk students as:

> Students scoring below 50 in at least one subject.

Performed:

* At-risk student identification
* Percentage analysis
* Group-wise risk comparison
* Root-cause analysis

### 5. Executive Reporting

Prepared a Principal's Report containing:

* Executive Summary
* Key Findings
* Strategic Recommendations

---

## 📈 Key Findings

### 📚 Test Preparation Matters

Students who completed the test preparation course achieved significantly higher average scores than students who did not.

### 🎓 Parental Education Impact

Students whose parents hold Bachelor's or Master's degrees generally perform better academically.

### 🔗 Strong Subject Correlation

Reading and Writing scores exhibit an extremely strong positive correlation (0.95).

### 👩 Gender-Based Performance Trends

* Female students outperform in Reading and Writing.
* Male students perform slightly better in Mathematics.

### ⚠️ At-Risk Student Groups

Students without test preparation and students from lower parental education backgrounds represent the highest-risk groups.

---

## 💡 Recommendations

### 1. Expand Test Preparation Programs

Provide structured preparation courses for all students, especially those identified as academically vulnerable.

### 2. Early Intervention System

Implement an early-warning framework to identify and support at-risk students before academic performance declines further.

### 3. Increase Parent Engagement

Conduct workshops and communication programs to encourage parental involvement in student learning.

---

## 📷 Sample Visualizations

### Scores by Parental Education

<img width="1000" height="600" alt="boxplot" src="https://github.com/user-attachments/assets/4d4570a0-cc48-4bcb-8e47-dae392e91e47" />


### Test Preparation Impact

<img width="640" height="480" alt="barplot" src="https://github.com/user-attachments/assets/42b3441f-052e-4aa0-8c00-f397f6491d8e" />


### Gender vs Subject Scores

<img width="800" height="500" alt="genderbarplot" src="https://github.com/user-attachments/assets/48dc04fb-1578-4ec6-a58b-962393defc99" />


### Subject Correlation Heatmap

<img width="800" height="600" alt="heatmap" src="https://github.com/user-attachments/assets/31f6d1c2-5522-4e4c-ab87-86c42cd1c967" />


### Total Score Distribution

<img width="800" height="500" alt="histplot" src="https://github.com/user-attachments/assets/bd522586-a26f-4dca-a54b-5e319e59c286" />

---


## 📁 Project Structure

Student-Performance-Analysis/
│
├── data/
│   └── StudentsPerformance.csv
│
├── notebooks/
│   └── Student_Performance_Analysis.ipynb
│
├── visuals/ Student_Performance_Visual_Report.pdf
│   ├── boxplot.png
│   ├── barplot.png
│   ├── genderbarplot.png
│   ├── heatmap.png
│   └── histplot.png
│
├── reports/
│   ├── Principal_Report_Students_Performance_Analysis.pdf
│   └── Student_Performance_Visual_Report.pdf
│



---

## 🚀 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning & Preparation
* Feature Engineering
* Statistical Analysis
* Data Visualization
* Business Insight Generation
* Stakeholder Reporting
* Educational Data Analytics

---



