# Data Professionals Survey - Power BI Project

## 📊 Overview
This project analyzes survey data from data professionals using **Power BI**.  
The dataset includes information on salaries, job titles, favorite programming languages, industries, countries, and work-life balance satisfaction.

The goal is to clean the dataset, transform it into usable formats, and create interactive visualizations that provide insights into the data professional community.

---

## 🛠 Data Preparation
- Deleted empty columns for cleaner structure.
- Processed **Salary column**:
  - Split ranges like `120k-150k` into min/max values.
  - Created a new column to calculate average salary.
- Cleaned **Job Title, Programming Language, Industry, Country**:
  - Split by custom delimiters to separate listed options from "Other. Specify".
- Ensured consistent formatting across all categorical fields.

---

## 📈 Visualizations
1. **Card** – Total number of survey takers  
2. **Card** – Average age of participants  
3. **Stacked Bar Chart** – Average salary by job title  
4. **Stacked Column Chart** – Favorite programming language by job title  
5. **Tree Map** – Geographic distribution of survey takers  
6. **Gauge** – Happiness with work/life balance  
7. **Gauge** – Happiness with current salary  
8. **Donut Chart** – Difficulty of entering the industry  

---

## 📂 Repository Structure

