# 📊 Tableau Project - HR Dashboard

## 📝 User Story - HR Dashboard

As an HR manager, I want a comprehensive dashboard to analyze human resources data, providing both summary views for high-level insights and detailed employee records for in-depth analysis.

---

## 📌 Summary View

The summary view is divided into three main sections:

### **1️⃣ Overview**
- Display the total number of hired employees, active employees, and terminated employees.
- Visualize the total number of hired and terminated employees over the years.
- Present a breakdown of total employees by department and job titles.
- Compare total employees between headquarters (HQ) and branches (New York is the HQ).
- Show the distribution of employees by city and state.

### **2️⃣ Demographics**
- Present the gender ratio in the company.
- Visualize the distribution of employees across age groups and education levels.
- Show the total number of employees within each age group.
- Show the total number of employees within each education level.
- Present the correlation between employees’ educational backgrounds and their performance ratings.

### **3️⃣ Income Analysis**
- Compare salaries across different education levels for both genders to identify any discrepancies or patterns.
- Present how age correlates with salary for employees in each department.

---

## 📂 Employee Records View
- Provide a comprehensive list of all employees with details such as name, department, position, gender, age, education, and salary.
- Users should be able to filter the list based on any of the available columns.

---

## 🔢 Data Generation

### **Chat-GPT Prompt for Data Generation**

Generate a Python script to create a realistic dataset of **8,950** HR records with the following attributes:

- **Employee ID**: A unique identifier.
- **First Name & Last Name**: Randomly generated.
- **Gender**: 46% probability for ‘Female’, 54% probability for ‘Male’.
- **State & City**: Randomly assigned from a predefined list.
- **Hire Date**: Randomly generated with custom probabilities for each year (2015-2024).
- **Department**: Randomly chosen from a list with specified probabilities.
- **Job Title**: Selected based on the department, with specific probabilities.
- **Education Level**: Determined based on job title and predefined mappings.
- **Performance Rating**: ‘Excellent’, ‘Good’, ‘Satisfactory’, ‘Needs Improvement’ (with specified probabilities).
- **Overtime**: 30% probability for ‘Yes’, 70% probability for ‘No’.
- **Salary**: Based on department and job title, within specific ranges.
- **Birth Date**: Aligned with age group distribution and job title requirements.
- **Termination Date**: Assigned to 11.2% of employees with controlled probabilities (ensuring at least a 6-month gap from the hire date).
- **Adjusted Salary**: Calculated using gender, education level, and age, with specific multipliers and increments.



---
