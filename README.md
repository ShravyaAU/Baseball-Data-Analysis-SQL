# ⚾ MLB SQL Analytics Pipeline

An end-to-end SQL analytics project built on 60,000+ Major League Baseball (MLB) records to answer real-world analytical questions related to player performance, salaries, schools, and career progression.  
This project demonstrates SQL-based data modeling, analytical transformations, and performance-optimized querying.

---

## 🎯 Project Goals

This project simulates how a Data Engineer or Analytics Engineer would build curated analytical datasets for downstream reporting teams.  
The objectives include:

- Identifying schools that produce the most MLB players  
- Analyzing salary trends across teams and decades  
- Understanding player career longevity and progression  
- Studying physical attributes (height, weight, handedness)  
- Creating reusable SQL transformations for BI consumption  

---

## 🛠️ Tech Stack

- **Database:** SQL Server  
- **SQL Concepts:** Joins, CTEs, Window Functions, Aggregations, Subqueries  
- **Data Modeling:** Star-schema style analytical tables  
- **Output:** CSV exports for dashboards and reporting  

---

## 🧱 Data Model (Simplified ERD)
Players ─────────┐ ├── Salaries Schools ──────────┘

- **Players:** Player attributes, demographics, handedness  
- **Schools:** College attended  
- **Salaries:** Salary by year, team, and league  

This structure supports analytical queries across multiple dimensions.

---

## 🔄 Pipeline Workflow
Raw Data → Staging Tables → Cleaned Tables → Analytical Views → Insights/Exports


### **1. Raw Data**
Imported CSV files into SQL Server.

### **2. Staging**
Basic cleaning:
- Standardized column names  
- Removed nulls and duplicates  
- Normalized school names  

### **3. Cleaned Tables**
Applied transformations:
- Derived metrics (BMI, career length, etc.)  
- Standardized date formats  
- Mapped players to schools and salary history  

### **4. Analytical Views**
Created SQL views for:
- Top schools producing MLB players  
- Salary trends by decade  
- Longest-serving players  
- Attribute distributions  

### **5. Exports**
Final datasets exported as CSV for BI tools.

---

## 📊 Key Insights

- **Top Schools:** USC and Arizona State University produced the highest number of MLB players  
- **Salary Trends:** Sharp salary growth post-1980s due to commercialization  
- **Career Longevity:** Several players maintained careers spanning 20+ years  
- **Physical Attributes:** Average height and weight increased over decades  
- **Handedness:** Right-handed players dominate, but left-handed pitchers remain highly valued  

---

## 📁 Repository Structure
MLB ANALYSIS │ ├── Queries │     ├── player career analysis │     ├── player comparison analysis │     ├── salary analysis │     └── school analysis │ ├── results │     ├── player career analysis │     ├── player comparison analysis │     ├── salary analysis │     └── school analysis │ └── README.md


---

## 🚀 How to Run This Project

1. Clone the repository  
2. Import raw CSV files into SQL Server  
3. Run staging scripts  
4. Run cleaned table scripts  
5. Run analytical view scripts  
6. Query the views or export results  

---

## 📌 Purpose of This Project

This project demonstrates how SQL can be used to:

- Build analytical datasets  
- Model relationships between entities  
- Optimize queries for reporting  
- Extract insights for sports analytics teams  


---

## 🔗 Repository Link

All SQL scripts and documentation are available here:  
👉 *Add your repo link here if needed*



