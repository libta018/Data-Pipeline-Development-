## TASK 1-DATA PIPELINE DEVELOPMENT

Author: Bisma yb

Domain: Data Science



# Laptop-Price-Prediction-Data-Pipeline

Data pipeline for preprocessing laptop price data using Pandas &amp; Scikit-Learn.
.

📌 Project Overview
This project builds a data preprocessing pipeline for a laptop price dataset.
The pipeline performs:
Data cleaning (handling missing values, fixing inconsistencies).
Feature transformation (scaling, encoding categorical variables).
Saving the preprocessed dataset for modeling.

📂 Dataset Overview
Dataset: laptop_prices.csv
📊 Total Records: 11,768

🛠 Features:
Categorical: Brand, Processor, Storage, GPU, Resolution, Operating System
Numerical: RAM (GB), Screen Size (inch), Battery Life (hours), Weight (kg), Price ($)



✅ Step 1: Load Data
Reads laptop_prices.csv and displays insights.

✅ Step 2: Handle Missing Values

Numerical Columns → Mean imputation
Categorical Columns → Most frequent value

✅ Step 3: Transform Features

One-Hot Encoding → Brand, Processor, etc.
Standard Scaling → RAM (GB), Battery Life (hours), etc.
Feature Engineering → Extracts numeric values from Storage.

✅ Step 4: Save Processed Data
Saves a cleaned dataset: processed_laptop_prices.csv


📈 Key Insights
High-end GPUs & Processors impact price significantly.
More RAM & SSD storage = Higher price.
Screen resolution (4K vs. 1080p) also affects pricing.







