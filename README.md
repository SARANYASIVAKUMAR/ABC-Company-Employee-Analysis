# ABC-Company-Employee-Analysis
Module 1 End Project – Employee Data Analysis
# ABC Company Employee Data Analysis (Module 1 End Project)

## Overview
This project performs a comprehensive analysis of employee data from ABC Company.
The dataset contains 458 records and 9 attributes related to employees, including
team, position, age, salary, and height.

The objective of this project is to preprocess the data, analyze employee
distribution and salary patterns, visualize insights, and present meaningful
conclusions using Python.

---

## Dataset
- Total Records: 458
- Total Columns: 9
- File Included: `ABC_company_dataset.xlsx`

---

## Preprocessing
- The `height` column contained inconsistent values.
- It was corrected by replacing all entries with random integers between **150 and 180**
  to ensure consistency and data integrity.

---

## Analysis Tasks Performed

### 1. Team Distribution
- Calculated the number of employees in each team.
- Computed percentage contribution of each team.
- Visualized using a bar chart.

### 2. Position Distribution
- Segregated employees based on position.
- Visualized the distribution using a horizontal bar chart.

### 3. Age Group Analysis
- Grouped employees into age categories.
- Identified the predominant age group in the organization.
- Visualized using a bar chart.

### 4. Salary Expenditure Analysis
- Identified the team with the highest total salary expenditure.
- Identified the position with the highest total salary expenditure.
- Visualized using bar charts.

### 5. Age vs Salary Relationship
- Analyzed correlation between age and salary.
- Visualized using a scatter plot with a trend line.

---

## Key Insights (Data Story)
- The workforce is fairly evenly distributed across teams.
- Shooting Guard (SG) is the most common position.
- The predominant age group is **26–35**, indicating a mid-career workforce.
- **Cleveland Cavaliers** have the highest total salary expenditure among teams.
- **Center (C)** position has the highest salary expenditure.
- Age and salary show a moderate positive relationship, indicating experience
  generally contributes to higher salary.

---

## Files in this Repository
- `ABC_company_project.ipynb` – Jupyter Notebook with full analysis and visualizations
- `ABC_company_dataset.xlsx` – Dataset used for analysis
- `README.md` – Project documentation

---

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Conclusion
This project demonstrates data preprocessing, exploratory data analysis,
visualization, and insight generation using real-world employee data.
