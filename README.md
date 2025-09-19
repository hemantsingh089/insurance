# insurance
🏥 Insurance Data Exploration 📊

Welcome to the Insurance Data Analysis project! This notebook dives into a health insurance dataset of 15,000 records to uncover trends and insights.

📁 Project Overview

This project explores health-related attributes and their impact on insurance claims. It demonstrates:

🧹 Data Cleaning – Handling missing values and understanding data types.

📈 Exploratory Data Analysis (EDA) – Visualizing distributions, relationships, and outliers.

🧮 Statistical Insights – Mean, median, and other descriptive stats.

🧾 Dataset Details

Rows: 15,000

Columns: 13

Key features:

👤 age, sex, weight, bmi

🧬 hereditary_diseases

🚭 smoker

🏙️ city

❤️ bloodpressure, diabetes, regular_ex

💼 job_title

💵 claim (insurance claim amount)

🔧 Steps in the Notebook

Data Loading – pandas used to import CSV.

Missing Value Check – Identified nulls in columns like age, bmi, claim.

Visualization –

seaborn distplots for numeric columns 🟦

Boxplots & countplots for categorical distributions 🟩

Key Findings –

Average age ≈ 39.5 years

Mean claim ≈ $13,401

BMI ranges widely (16–53) 🍔💪

🛠️ Tech Stack

🐍 Python

🐼 pandas

📊 seaborn & matplotlib

📝 Google Colab

🚀 How to Run

Clone or download the repo.

Open the notebook in Google Colab or Jupyter.

Run cells sequentially to reproduce the analysis.

💡 Next Steps

Build predictive models to estimate insurance claims.

Feature engineering (e.g., smoker status impact).
