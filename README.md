# 🏥 Healthcare Data Analysis Project

## 📌 Project Overview

This project explores a healthcare dataset originally stored in a Microsoft SQL Server `.bak` backup. The goal is to analyze trends, patterns, and relationships within the data using **SQL** and later visualize insights using **Power BI**.

The project involves multiple phases:
- Converting the raw database into a usable format (MySQL)
- Structuring and cleaning data
- Running analytical SQL queries
- Building interactive dashboards for insights

---

## 📂 Data Source

- Original file: `healthcare_database.bak`
- Source system: Microsoft SQL Server
- Contains: 10 relational tables related to healthcare operations

---

## 🔄 Phase 1: Data Extraction and Migration

**Tools Used:**  
- SQL Server Management Studio (SSMS)  
- MySQL Workbench / Command Line  
- CSV file export/import

**Steps Completed:**
1. Restored the `.bak` file using SSMS
2. Exported all 10 tables to `.csv` format
3. Imported all 10 tables into **MySQL**
   - Verified correct structure and row counts
   - Resolved date format issues automatically
   - No problems with special characters or nulls

---

## 🧪 Current Status

- ✅ Data successfully migrated to MySQL
- ✅ Verified all tables and values after import
- ⏳ In progress: Updating column data types for accuracy (e.g., `INT`, `VARCHAR`, `DATE`)
- ⏳ Preparing for analytical queries and visual dashboards

---

## 🧭 Next Steps

- [ ] Finalize data type adjustments in MySQL
- [ ] Create Entity Relationship Diagram (ERD)
- [ ] Write SQL queries for exploration and KPIs
- [ ] Develop Power BI dashboard
- [ ] Complete documentation and insights write-up

---

## 🧰 Tools & Technologies

- SQL Server Management Studio (SSMS)
- MySQL & MySQL Workbench
- CSV
- Power BI / Tableau (upcoming)
- Git & GitHub for version control
- Markdown for documentation

---

## 📁 Project Structure


