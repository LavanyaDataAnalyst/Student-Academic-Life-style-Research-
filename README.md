# 📊 Student Lifestyle & Academic Analysis
## ℹ️ Description:
* This study examines how students’ daily habits and learning styles influence their exam results. 
* Using data from an academic dataset, it applies cleaning and BI visualization to identify meaningful patterns. 
* The analysis leverages Excel for data preparation and Power BI (with DAX measures) for modeling and dashboards.
  
## 📖 Table of Contents:
>* Project Overview
>* Data Source
>* Tools & Technologies
>* Data Cleaning & Preparation
>* Exploratory Data Analysis (EDA)
>* Key Insights
>* Recommendations
>* How to Use

## 📘Project Overview:
- The project aims to understand the impact of lifestyle factors (study hours, sleep, social media use, etc.) and learning styles (Kinesthetic, Reading/Writing, Auditory, Visual) on academic performance. 
- Key objectives include analyzing student study habits, comparing performance across learning styles and gender, and identifying factors that influence exam scores.

## 🗂 Data Source:
* The dataset (education domain) was sourced from `DeepDataLake.com`
* It contains student records with fields such as age, gender, weekly study hours, preferred learning style, number of online courses completed, discussion participation, assignment completion rate, exam score (%), attendance rate (%), use of educational technology, self-reported stress level, weekly social media hours, nightly sleep hours, and final grade.
* This multi-dimensional data enables comprehensive analysis of lifestyle versus performance.
 
## 🛠 Tools & Technologies:
* Microsoft Excel and Power BI are the primary tools. 
* **Excel** was used for data cleaning (pivot tables, sorting, filtering) and initial exploration. 
* **Power BI handled data modeling and visualization:** the model includes eight related tables to ensure data integrity. 
* **Custom DAX measures, calculated tables and calculated columns** were implemented to create categories like Sleep Level (Insufficient/Adequate), Usage Level (Minimal/Casual/Regular), Study Level (Minimal/Light/Regular/Dedicated), and Performance Level (Top/Average/Low).
* **Interactive dashboards** (bar charts, KPIs, filters) summarize key metrics by student segments.

## 🧹Data Cleaning & Preparation

- Cleaned and structured the dataset using Microsoft Excel.

- Converted categorical values (Yes/No) into numeric format for analysis.

- Checked and removed duplicate or missing records.

- Organized data by Student ID and segmented by learning style.

- Created pivot tables to summarize study hours, sleep, and exam scores.

## 📊 Exploratory Data Analysis (EDA)

- Analyzed relationships between study hours, sleep, social media use, and exam scores.

- Compared performance across learning styles (Visual, Kinesthetic, Auditory, Reading/Writing).

- Evaluated impact of attendance, assignments, and participation on grades.

- Conducted gender-based analysis for course completion and performance.

- Visualized trends using Power BI charts and dashboards.

![EDA Analysis](images/eda.png)
>Figure: Comparison of study habits and academic performance across different learning styles.

## 🔍 Key Insights

- Students studying **11–20 hours per week** showed consistent academic performance.

- **6–8 hours of sleep** was linked with stable exam scores.

- Excessive **social media usage** slightly reduced performance levels.

- Active participation and use of educational technology improved outcomes.

- Stress levels were higher among younger students but had limited effect on scores.

## 💡Recommendations

- Encourage **structured study schedules** for better time management.

- Promote **healthy sleep habits** to support learning efficiency.

- Limit excessive **screen and social media time.**

- Increase **student engagement** through discussions and learning platforms.

- Motivate students to complete **online certifications and skill courses.**

## ▶️ How to Use

- Open the Power BI dashboard included in the project files.

- Use filters and slicers to explore different student segments.

- Analyze KPIs such as Top Performers, Attendance Rate, and Study Intensity.

- Compare lifestyle factors with academic outcomes through visual reports.

- Use insights to support data-driven academic decision-making.

## 👩‍💻 Author
 > Lavanya Madhan Raj

