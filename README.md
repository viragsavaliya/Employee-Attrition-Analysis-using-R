# Employee Attrition Analysis

## 📌 Project Overview
Employee attrition, or turnover, is a critical issue for organizations as it impacts productivity, morale, and operational costs. This project aims to analyze key factors contributing to employee attrition using statistical and data visualization techniques. The insights from this analysis can help businesses develop retention strategies and improve workplace satisfaction.

## 🔍 Objectives
- Identify the main factors influencing employee attrition.
- Use statistical methods to analyze correlations between different attributes.
- Visualize key patterns and trends using data visualization techniques.
- Provide actionable insights to help reduce employee turnover.

## 📂 Dataset
The dataset used in this analysis contains employee records with the following attributes:
- **Satisfaction Level**: Employee job satisfaction score.
- **Last Evaluation**: Employee performance evaluation score.
- **Number of Projects**: Number of projects an employee has worked on.
- **Average Monthly Hours**: Time spent working per month.
- **Time Spent at Company**: Years an employee has worked at the company.
- **Department**: Employee's department (e.g., Sales, HR, R&D).
- **Salary**: Employee salary category (Low, Medium, High).
- **Left**: Whether the employee left the company (Yes/No).

## 📊 Methodology
1. **Data Preprocessing**
   - Load the dataset and handle missing values if any.
   - Convert categorical variables into appropriate formats.
   - Normalize/standardize numerical features if necessary.

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics of the dataset.
   - Visualization of attrition trends by department, tenure, and salary levels.
   - Analysis of factors like satisfaction level, workload, and promotions.

3. **Statistical Analysis**
   - **Chi-Square Test**: To determine correlations between categorical variables (e.g., salary vs. attrition).
   - **Boxplots & Histograms**: To observe distributions of numerical features.
   - **Bar Charts**: To visualize trends across different categories.

4. **Findings & Insights**
   - Employees with **low satisfaction levels** are more likely to leave.
   - High **workload and excessive working hours** contribute to attrition.
   - Employees in **certain departments** (HR, Accounting) show higher attrition rates.
   - **Salary and promotion opportunities** significantly impact retention.

## 🛠 Implementation
- **Programming Language**: R
- **Libraries Used**:
  - `ggplot2` (Data Visualization)
  - `dplyr` (Data Manipulation)
  - `tidyr` (Data Cleaning)
  - `chisq.test()` (Statistical Testing)

## 📈 Key Visualizations
- **Satisfaction Level Histogram**: Shows distribution of employee satisfaction.
- **Attrition by Department**: Highlights departments with higher attrition rates.
- **Time Spent at Company Analysis**: Identifies tenure groups most likely to leave.
- **Salary vs. Attrition Rate**: Examines how salary levels impact turnover.

## 📌 Conclusion
- Employees with **3-5 years of experience** are most likely to leave.
- **Management and R&D departments** have the highest median satisfaction.
- Employees in **HR and Accounting** report the lowest satisfaction.
- The **lack of promotions** in IT and Product Management departments contributes to higher attrition.

## 🙌 Acknowledgment
We would like to thank our mentors and faculty for their guidance and support throughout this project.

## 🚀 Future Work
- Implement machine learning models to predict attrition probability.
- Explore other influencing factors such as benefits, work-life balance, and company policies.
