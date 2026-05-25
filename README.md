#  End-to-End Train Schedule Data Engineering Pipeline

##  Internship Project — Sysslan IT Solutions
**Intern:** Wilson Katam
**Domain:** Data Engineering
**Reference ID:** SYS-2025-INT-12056

---

##  Project Overview
This project focuses on applying data engineering 
principles to build a structured and reliable 
data pipeline for train schedule data covering 
1,86,074 records across 11,113 trains and 
8,147 stations.

---

##  Tech Stack
- Python
- PySpark 3.5.0
- Docker
- Jupyter Lab
- Pandas
- Matplotlib
- Scikit-learn
- GitHub

---

##  Dataset
- Total Records: 1,86,074
- Total Trains: 11,113
- Total Stations: 8,147
- Source: Indian Railways Schedule Data

---

##  Project Structure

### Level 1 — Data Ingestion & Inspection
- Loaded dataset using Python and PySpark
- Verified 1,86,074 records and 12 attributes
- Reviewed schema and data types
- Preserved raw data backup

### Level 2 — Data Cleaning & Validation
- Identified and handled missing values
- Detected and removed duplicate records
- Standardized time formats to HH:MM:SS
- Saved validated dataset

### Level 3 — Data Transformation
- Converted time fields to datetime format
- Calculated journey duration per train
- Organized records by train and station sequence
- Prepared dataset for downstream reporting

### Level 4 — Structured Tables & Aggregations
- Generated train-level stops table
- Generated train-level distance table
- Created cross table — 11,113 x 8,147
- Exported all structured tables

### Level 5 — Visualization & Basic Prediction
- Visualized top 10 trains by stops and distance
- Plotted journey duration distribution
- Train-test split — 80/20
- Built Linear Regression model — R2: 0.21

### Level 6 — Final Decision Tree Model
- Built Decision Tree Regressor
- Max depth: 4
- MAE: 95.66
- R2 Score: 0.50
- Visualized complete decision tree

---

##  Model Comparison
| Model | MAE | R2 Score |
|-------|-----|----------|
| Linear Regression | 166.32 | 0.21 |
| Decision Tree | 95.66 | 0.50 |

---

##  Files
| File | Description |
|------|-------------|
| Level1_Data_Ingestion.ipynb | Data loading & inspection |
| Level2_Data_Cleaning.ipynb | Data cleaning & validation |
| Level3_Data_Preparation.ipynb | Transformation & features |
| Level4_Structured_Tables.ipynb | Aggregations & tables |
| Level5_Visualization.ipynb | Charts & basic ML |
| Level6_Decision_Tree.ipynb | Final ML model |

---

##  Acknowledgement
Thank you **Sysslan IT Solutions** for this 
incredible internship opportunity!

## Wilson Katam
