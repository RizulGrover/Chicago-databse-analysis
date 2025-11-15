# Chicago-databse-analysis
End-to-end SQL analysis using Python and SQLite on Chicago datasets. Includes data exploration, filtering, aggregations, and joins to uncover insights on crime, schools, and socioeconomic trends.


# Chicago Data Analysis Using SQL & Python

This project explores real-world datasets from the City of Chicago using **SQLite** integrated with **Python**.  
The goal is to run SQL queries directly inside Python to uncover insights about communities, public schools, and crime patterns.

##  Datasets Used
The SQLite database contains three tables created from public Chicago datasets:

- **Chicago Socioeconomic Indicators**
- **Chicago Public Schools**
- **Chicago Crime Data**

These datasets allow for a multi-dimensional analysis of demographics, school performance, and crime levels across Chicago’s community areas.

---

##  Project Objectives
Using Python and SQLite, this project focuses on:

- Loading and exploring relational datasets  
- Executing SQL queries programmatically  
- Filtering and extracting meaningful information  
- Grouping, aggregating, and comparing results   
- Deriving insights by combining SQL logic with Python  

This notebook demonstrates practical SQL usage in a real Python workflow
---

##  Analysis Workflow

### **1. Dataset Understanding**
- Loaded all three datasets into SQLite tables.
- Inspected table structures, column types, and distribution of values.

### **2. Basic SQL Retrieval**
- Queried counts, unique values, and simple descriptive statistics.
- Reviewed dataset coverage and completeness.

### **3. Filtering & Conditional Extraction**
- Identified communities with high crime numbers.
- Extracted schools that scored above/below certain metrics.
- Pulled socioeconomic indicators for targeted areas.

### **4. Aggregations & Group-Level Insights**
Used SQL aggregate functions (`AVG`, `SUM`, `COUNT`, `MIN`, `MAX`) to explore:

- Crime levels by community area  
- Average school performance indicators  
- Income and hardship index comparisons  
- Total vs. average values across categories  

### **5. Multi-Table Joins**
Performed SQL joins across the three datasets to find relationships:

- Crime levels correlated with socioeconomic hardship  
- Schools in areas with lower income tended to score lower academically  
- Community areas with lower education levels showed higher crime density  

### **6. Key Insights (Conclusion)**

#### **Socioeconomic Patterns**
- Community areas with **lower median income** and **higher hardship index scores** consistently displayed higher crime counts.  
- Areas with strong socioeconomic indicators generally reported better school performance.

#### **School Performance Observations**
- Schools located in wealthier neighborhoods tended to show **higher average ratings**, attendance percentages, and reading/math proficiency.

#### **Crime Distribution**
- Crime was heavily concentrated in a few community areas.
- Certain high-crime regions also showed low socioeconomic standings, highlighting clear correlations.

#### **Cross-Dataset Relationships**
- Joining socioeconomic indicators with crime data revealed a **negative correlation between income and crime levels**.
- Joining school performance with socioeconomic data reinforced the link between community education levels and student achievement.

These insights collectively show how SQL can be used to extract, join, and analyze structured data in a meaningful way using Python.

---

##  Technologies Used
- **Python**  
- **SQLite**  
- **Pandas**  
- **SQL in Jupyter Notebook**  

---


---

##  How to Run This Project
1. Clone the repository  
2. Ensure you have SQLite installed (or use built-in support in Python)  
3. Open the notebook  
4. Run all cells — the database file is included  



