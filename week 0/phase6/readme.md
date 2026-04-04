# Phase 6 – Spark Playground Exit Sprint (Advanced Practice)

🔹 **Objective**
In this phase, the goal is to strengthen PySpark skills by practicing joins, window functions, date operations, and building a complete data pipeline. This phase focuses on improving speed, accuracy, and confidence before working in Databricks.

---

🔹 **Problem Summary**
We were given a sample dataset containing customers and orders with some dirty data.

The task was to:
• Clean and validate the dataset
• Identify invalid records
• Perform joins between tables
• Apply transformations and aggregations
• Use window functions for analysis
• Build a complete pipeline and save output

---

🔹 **Approach**

1. Loaded dataset into PySpark DataFrames
2. Performed data cleaning:

   * Removed null values
   * Filtered negative values
   * Trimmed string columns
3. Validated data using joins (left_anti for invalid records)
4. Joined datasets using correct keys
5. Applied transformations and aggregations
6. Used window functions for ranking and analysis
7. Saved final output

---

🔹 **Key Transformations Used**

• `dropna()` → remove null values
• `filter()` → remove invalid data
• `trim()` → clean string columns
• `join()` → combine datasets
• `groupBy()` → aggregation
• `agg()` → calculate metrics (sum, count)
• `window functions` → ranking and analysis

---

🔹 **Tasks Performed**

• Identified invalid customer records using left_anti join
• Performed inner and left joins
• Calculated total spend per customer
• Counted number of orders
• Ranked customers based on spend
• Practiced date-based operations

---

🔹 **Output / Results**

The following outputs were generated:
• Cleaned and validated dataset
• Customer-level metrics (total spend, total orders)
• Ranked customer dataset
• Final output saved to storage

---

🔹 **Data Engineering Considerations**

• Ensured data quality by removing nulls and invalid values
• Validated referential integrity between tables
• Avoided incorrect joins and duplication
• Verified results using sample checks

---

🔹 **Challenges Faced**

• Handling null and invalid data
• Identifying incorrect foreign keys
• Writing correct join conditions
• Understanding window functions
• Managing proper pipeline flow

---

🔹 **Learnings**

• Improved understanding of joins and validation
• Learned how to clean real-world datasets
• Gained confidence in window functions
• Understood complete ETL pipeline execution
• Improved debugging and problem-solving skills

---

🔹 **Pipeline Overview**

1. Data Ingestion → Load datasets
2. Data Cleaning → Handle nulls and invalid values
3. Data Validation → Check referential integrity
4. Data Transformation → Join and aggregate
5. Analytics → Apply window functions
6. Output → Save final dataset

---

🔹 **Files in this Folder**

• solution.py / notebook → PySpark implementation
• starter code → practice dataset
• outputs/ → result outputs
• README.md → documentation

---
