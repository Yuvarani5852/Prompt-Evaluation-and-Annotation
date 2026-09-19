# Coding Prompts

## Overview
This file contains 15+ prompts designed and tested for coding tasks across ChatGPT, Claude AI, and GitHub Copilot. Each prompt includes context, prompt text, expected output, and LLM used.

---

## Category 1: Python Data Analysis

### Prompt 1
**Context:** Data cleaning function
**Prompt:**
> "Write a reusable Python function called 'clean_dataframe' that accepts a Pandas DataFrame and: 1) Removes duplicates, 2) Fills numeric nulls with median, 3) Fills categorical nulls with mode, 4) Strips whitespace from string columns, 5) Returns cleaned DataFrame with a summary report."

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** Clean, reusable Python function
**Best Performer:** GitHub Copilot

---

### Prompt 2
**Context:** EDA automation
**Prompt:**
> "Write a Python script that automatically generates an EDA report for any CSV file. Include: shape, dtypes, null counts, duplicate count, summary statistics, and save 3 plots (distribution, correlation heatmap, boxplot) as PNG files."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Automated EDA script
**Best Performer:** Claude AI

---

### Prompt 3
**Context:** Feature engineering
**Prompt:**
> "I have a datetime column called 'Date' in a Pandas DataFrame. Write Python code to extract: Year, Month, Month Name, Quarter, Day of Week, Is Weekend, Is Holiday (for Indian public holidays in 2025). Use appropriate libraries."

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** Feature engineering code
**Best Performer:** ChatGPT

---

### Prompt 4
**Context:** Data aggregation
**Prompt:**
> "Write Python code using Pandas groupby to calculate: 1) Average congestion by area, 2) Total incidents by weather condition, 3) Peak traffic hour by road, 4) Weekday vs weekend average speed. Dataset: banglore_traffic_cleaned.csv"

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** Aggregation code with multiple groupby operations
**Best Performer:** GitHub Copilot

---

### Prompt 5
**Context:** Visualization function
**Prompt:**
> "Write a reusable Python function called 'plot_top_n' that accepts a DataFrame, a column name, n (default 10), and a title. It should plot a horizontal bar chart of top N values sorted in descending order with proper formatting and save it as PNG."

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** Reusable plotting function
**Best Performer:** GitHub Copilot

---

## Category 2: SQL Queries

### Prompt 6
**Context:** Complex JOIN query
**Prompt:**
> "Write a SQL query to join three tables: customers (customer_id, name, city), orders (order_id, customer_id, product_id, amount, date), products (product_id, name, category). Find top 5 customers by total spend in each city for 2025."

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** Complex JOIN with window functions
**Best Performer:** Claude AI

---

### Prompt 7
**Context:** Stored procedure
**Prompt:**
> "Write a SQL stored procedure called 'get_monthly_report' that accepts year and month as parameters and returns: total sales, average order value, top product, and customer count for that month from a sales table."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** SQL stored procedure
**Best Performer:** ChatGPT

---

### Prompt 8
**Context:** Query optimisation
**Prompt:**
> "I have a slow SQL query that joins 3 large tables and uses multiple subqueries. Explain 5 ways to optimise it for better performance. Include examples of using indexes, CTEs instead of subqueries, and avoiding SELECT *."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Query optimisation techniques with examples
**Best Performer:** Claude AI

---

## Category 3: Python Automation

### Prompt 9
**Context:** Automated report generation
**Prompt:**
> "Write Python code to automatically generate a weekly sales report from a CSV file. The report should include: total sales, top 5 products, regional breakdown, and week-over-week change. Save the report as a formatted text file with today's date in the filename."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Automated reporting script
**Best Performer:** ChatGPT

---

### Prompt 10
**Context:** File processing automation
**Prompt:**
> "Write Python code to monitor a folder for new CSV files, automatically read each new file, clean it (remove nulls and duplicates), and save the cleaned version to an 'output' folder with 'cleaned_' prefix. Use the watchdog library."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** File monitoring and processing script
**Best Performer:** ChatGPT

---

## Category 4: Machine Learning Basics

### Prompt 11
**Context:** Classification model
**Prompt:**
> "Write Python code to build a Random Forest classifier to predict Congestion_Category (Low/Moderate/High/Severe) based on Traffic_Volume, Avg_Speed, Weather, and Is_Weekend. Include preprocessing, train-test split, model training, and evaluation (accuracy, classification report)."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Complete ML pipeline
**Best Performer:** Claude AI

---

### Prompt 12
**Context:** Model evaluation
**Prompt:**
> "Write Python code to compare 3 classification models (Logistic Regression, Random Forest, XGBoost) on the same dataset. Create a comparison table showing accuracy, precision, recall, F1-score, and training time for each model."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Model comparison code
**Best Performer:** Claude AI

---

### Prompt 13
**Context:** Time series forecasting
**Prompt:**
> "Write Python code to forecast next 3 months of traffic volume using Facebook Prophet library. Input: monthly average traffic data for 2022-2025. Show actual vs predicted plot and print forecast values with confidence intervals."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Prophet forecasting code with visualization
**Best Performer:** ChatGPT

---

## Category 5: Code Debugging & Review

### Prompt 14
**Context:** Debugging Python code
**Prompt:**
> "Review this Python code for data cleaning and identify all bugs, inefficiencies, and improvements: [paste code]. Provide corrected version with explanations for each change."

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** Detailed code review with corrections
**Best Performer:** GitHub Copilot

---

### Prompt 15
**Context:** Code documentation
**Prompt:**
> "Add proper docstrings, inline comments, and type hints to this Python function that calculates RFM scores. Follow Google style docstring format. Also suggest a better function name if applicable."

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** Well-documented code
**Best Performer:** GitHub Copilot
