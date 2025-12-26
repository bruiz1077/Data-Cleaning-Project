# Data-Cleaning-Project
A full data‑cleaning workflow applied to the Nashville Housing dataset, including date normalization, address parsing, categorical standardization, duplicate removal, and column optimization using SQL.

🧹 Nashville Housing Data Cleaning Project
A SQL‑based data cleaning project focused on transforming the Nashville Housing dataset into a clean, standardized, and analysis‑ready table. This project demonstrates practical skills in data quality improvement, feature extraction, and preparing real‑world datasets for analytics or reporting.

📌 Project Overview
This project applies a full data‑cleaning workflow to the Nashville Housing dataset. The goal is to correct inconsistencies, standardize formats, extract meaningful fields, and remove duplicate or unnecessary data. The final cleaned dataset is easier to query, analyze, and use for downstream BI or analytics tasks.

🛠️ Skills Demonstrated
- SQL data cleaning and transformation
- Standardizing date and string formats
- Handling missing or inconsistent values
- Splitting combined fields into usable components
- Removing duplicates
- Updating and optimizing table structure
- Practical ETL‑style problem solving

🧩 Key Cleaning Steps
- Standardized date formats for consistency
- Populated missing property addresses using self‑joins
- Split full addresses into Address, City, and State
- Separated OwnerAddress into individual components
- Normalized categorical values (e.g., “Y/N” → “Yes/No”)
- Removed duplicate records using window functions
- Dropped unused or redundant columns to streamline the table


📂 Project Structure
nashville-housing-cleaning/
│── sql/
│     └── nashville_data_cleaning.sql
│── README.md




