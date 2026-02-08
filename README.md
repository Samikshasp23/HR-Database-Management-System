# HR Database Management System (SQL Server)

## 📌 Project Overview
The **HR Database Management System** is a structured relational database built using **SQL Server** to manage and analyze Human Resources data efficiently.  
This project is designed for **learning, practice, and demonstration of SQL concepts**, including database design, normalization, constraints, and relational queries.

The database simulates a real-world HR system containing employee records, job roles, departments, dependents, and global organizational structure.

---

## 🗂️ Database Structure
The database consists of **seven interrelated tables**:

1. **Employees**
   - Stores employee personal details, salary, job role, manager, and department information.

2. **Jobs**
   - Defines job titles, job IDs, and salary ranges.

3. **Departments**
   - Contains department details and associated locations.

4. **Dependents**
   - Stores employee dependents for HR benefits and policy analysis.

5. **Locations**
   - Maintains physical office locations of departments.

6. **Countries**
   - Holds country information where the organization operates.

7. **Regions**
   - Groups countries into global regions such as Asia, Europe, America, and Middle East & Africa.

---

## 🔗 Relationships & Constraints
- **Primary Keys** uniquely identify each record.
- **Foreign Keys** maintain relationships between tables.
- Referential integrity ensures consistency across employees, departments, and dependents.
- Invalid foreign key references have been corrected (e.g., dependents linked only to existing employees).

---

## 📊 Sample Data
The project includes realistic sample data:
- **39 Employees**
- **29 Dependents**
- Multiple job roles, departments, locations, countries, and regions

This dataset enables meaningful SQL querying and analysis.

---

## 🧠 Key Learnings & Use Cases
- Practice **SQL fundamentals**:  
  `SELECT`, `WHERE`, `ORDER BY`, `DISTINCT`
- Perform **JOIN operations** across multiple tables
- Understand **primary key–foreign key relationships**
- Analyze employee hierarchy and departmental structure
- Learn **data normalization** and relational design
- Apply **indexing and optimization concepts**

---

## ⚙️ Technologies Used
- **Database:** Microsoft SQL Server  
- **Language:** SQL (T-SQL)
- **Tools:** SQL Server Management Studio (SSMS)

---

## 🚀 How to Run the Project
1. Open **SQL Server Management Studio (SSMS)**
2. Create a new database:
   ```sql
   CREATE DATABASE HR_Database;
