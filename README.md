# 📊 HR Workforce Analysis – Power BI Dashboard

## 📌 Project Overview

The **HR Workforce Analysis Dashboard** is an interactive Power BI project designed to analyze employee workforce data and provide data-driven insights into workforce size, employee attrition, salary structure, performance, and training investment.

The dashboard helps HR teams and management understand workforce trends and make better decisions using interactive filters, KPIs, charts, and detailed analysis.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze total and active employees
- Understand employee attrition trends
- Analyze attrition rate by department
- Compare annual hiring trends
- Analyze employee salary structure
- Compare average and median salaries
- Analyze total payroll cost
- Track training investment
- Compare salary across departments
- Analyze employee performance distribution
- Understand workforce distribution by career level
- Identify departments with higher and lower salary levels

---

## 🛠️ Tools & Technologies Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Microsoft Excel

---

## 📂 Dashboard Pages

This project contains 3 interactive dashboard pages:

### 1️⃣ Workforce Overview

The Workforce Overview page provides a high-level summary of the organization's employees.

### Key KPIs

- Total Employees
- Active Employees
- Attrition Rate
- Average Salary
- High Performance %
- Average Tenure
- Training Investment
- Female Workforce %

### Visualizations

- Active Headcount by Department
- Performance Distribution by Department
- Workforce by Career Level
- Department-wise Performance Analysis

### Filters

- Year
- Department Type
- Career Level Band

---

### 2️⃣ Attrition Analysis

The Attrition Analysis page focuses on employee turnover and hiring trends.

### Key KPIs

- Attrition Rate
- Terminated Employees
- YTD Attrition Rate
- New Hires

### Visualizations

- Annual Hiring vs Same Period Last Year
- Attrition Rate by Department
- Year-to-Date New Hires by Month

### Key Analysis

This page helps identify departments with higher attrition and understand employee hiring trends over different years.

### Filters

- Year
- Department Type

---

### 3️⃣ Compensation

The Compensation page provides insights into employee salary, payroll, and training investment.

### Key KPIs

- Average Salary
- Median Salary
- Total Payroll Cost
- Training Investment

### Visualizations

- Average Salary by Department
- Department Salary Ranking
- Above/Below Average Salary
- Training Cost by Department

### Filters

- Year
- Department Type
- Career Level Band
- Salary Band

---

## 📊 Key Insights

The dashboard provides several useful business insights:

- The organization has approximately 50K employees.
- Around 41K employees are active.
- Overall attrition rate is approximately 17.9%.
- Average employee tenure is around 4.7 years.
- Female employees represent approximately 56% of the workforce.
- Training investment is approximately ₹27.93M.
- Total payroll cost is approximately ₹3.49B.
- Production has the highest active headcount among the departments.
- Production also has the highest training investment.
- Attrition varies significantly across departments.
- Salary levels can be compared using department-wise salary analysis.
- Employee performance can be analyzed across different departments.

---

## 🔄 Data Preparation

The data was prepared using Power Query before creating the dashboard.

Main data preparation activities included:

- Data cleaning
- Removing unnecessary data
- Handling missing values
- Changing data types
- Creating required columns
- Preparing data for analysis
- Checking data consistency

---

## 🧮 DAX & Calculations

DAX was used to create important KPIs and analytical measures.

Important calculations included:

- Total Employees
- Active Employees
- Terminated Employees
- Attrition Rate
- Average Salary
- Median Salary
- Total Payroll Cost
- Training Investment
- High Performance %
- Average Tenure
- New Hires
- YTD calculations

Example DAX calculations used in the project:

Attrition Rate = DIVIDE([Terminated Employees], [Total Employees], 0)

Average Salary = AVERAGE(Employee[Salary])

Total Payroll Cost = SUM(Employee[Salary])

---

## 🔗 Data Modeling

A structured data model was created in Power BI to establish relationships between the required tables and support accurate calculations and filtering.

The data model helps to:

- Improve report performance
- Maintain data consistency
- Support interactive filtering
- Enable DAX calculations
- Create meaningful relationships between data

---

## 🎨 Dashboard Design

The dashboard uses a modern dark purple and pink theme.

Design features include:

- Dark background
- Purple and pink highlights
- KPI cards
- Interactive slicers
- Bar charts
- Donut charts
- Tables
- Department-wise analysis
- Consistent formatting
- User-friendly navigation

---

## 📈 Business Benefits

This dashboard can help HR teams to:

- Monitor workforce size
- Track employee attrition
- Identify high-attrition departments
- Analyze hiring performance
- Understand salary distribution
- Monitor payroll expenses
- Evaluate training investment
- Analyze employee performance
- Support HR decision-making

---

## 🚀 Skills Demonstrated

Through this project, I demonstrated skills in:

- Power BI Dashboard Development
- Data Cleaning
- Power Query
- DAX
- Data Modeling
- KPI Development
- Data Visualization
- HR Analytics
- Attrition Analysis
- Compensation Analysis
- Business Intelligence
- Interactive Dashboard Design

---

## 📁 Project Structure

HR-Workforce-Analysis/

├── HR_Workforce_Analysis.pbix

├── Dataset/

│   └── HR Workforce Dataset

├── Screenshots/

│   ├── Workforce Overview.png

│   ├── Attrition Analysis.png

│   └── Compensation.png

└── README.md

---

## 💡 Conclusion

The **HR Workforce Analysis Dashboard** transforms raw employee data into meaningful and interactive HR insights.

It provides a complete view of:

**Workforce → Attrition → Compensation → Performance → Training**

This project demonstrates how Power BI, Power Query, DAX, and data visualization can be used to solve real-world HR analytics problems and support data-driven decision-making.

---

## 👨‍💻 Author

**Hardik Kumar Kumhar**

Aspiring Data Analyst

### Skills

Excel | SQL | Power BI | Python | Power Query | DAX | Data Analytics

---

⭐ If you find this project useful, feel free to give it a star!
