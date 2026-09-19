# Data Analysis Prompts

## Overview
This file contains 20+ prompts designed and tested for data analysis tasks across ChatGPT, Claude AI, and GitHub Copilot. Each prompt includes the context, prompt text, expected output, and LLM used.

---

## Category 1: Data Cleaning & Preprocessing

### Prompt 1
**Context:** Cleaning a CSV dataset with missing values
**Prompt:**
> "I have a CSV dataset with 15,000 rows and 12 columns. Some columns have missing values and duplicates. Write Python code using Pandas to: 1) Check for missing values, 2) Fill numeric columns with median, 3) Fill categorical columns with mode, 4) Remove duplicate rows, and 5) Print a summary report."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Clean Python code with comments
**Best Performer:** Claude AI

---

### Prompt 2
**Context:** Handling outliers in a dataset
**Prompt:**
> "Write Python code to detect and remove outliers from a numerical column using the IQR method. The dataset is a Pandas DataFrame called 'df' and the column name is 'Salary'. Show before and after row counts."

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** Python code with IQR calculation
**Best Performer:** ChatGPT

---

### Prompt 3
**Context:** Data type conversion
**Prompt:**
> "I have a Pandas DataFrame where the 'Date' column is stored as a string in 'DD-MM-YYYY' format. Write code to convert it to datetime format and extract Year, Month, Day, and Day of Week as separate columns."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Code with datetime parsing and feature extraction
**Best Performer:** Claude AI

---

## Category 2: Exploratory Data Analysis (EDA)

### Prompt 4
**Context:** EDA on sales dataset
**Prompt:**
> "I have a sales dataset with columns: Date, Product, Region, Sales, Profit. Write Python code to perform EDA including: 1) Summary statistics, 2) Distribution plots for Sales and Profit, 3) Correlation heatmap, 4) Top 5 products by revenue, 5) Monthly sales trend."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Complete EDA code with Matplotlib and Seaborn
**Best Performer:** Claude AI

---

### Prompt 5
**Context:** Finding patterns in traffic data
**Prompt:**
> "I have a traffic dataset with columns: Area, Road, Traffic_Volume, Avg_Speed, Congestion_Level, Weather, Date. Write Python code to find: 1) Most congested areas, 2) Peak traffic hours, 3) Weather impact on congestion, 4) Weekday vs weekend comparison."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** EDA code with visualisations
**Best Performer:** Claude AI

---

### Prompt 6
**Context:** Customer segmentation analysis
**Prompt:**
> "Explain how to perform RFM (Recency, Frequency, Monetary) analysis on an e-commerce dataset using Python. Include code for calculating RFM scores and segmenting customers into High, Medium, and Low value groups."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** RFM analysis explanation with code
**Best Performer:** ChatGPT

---

## Category 3: SQL Query Generation

### Prompt 7
**Context:** Writing complex SQL queries
**Prompt:**
> "Write a SQL query using CTEs to find the top 5 most congested roads in each city, along with their average speed and total incidents. The table is called 'traffic' with columns: city, road, congestion_level, avg_speed, incidents, date."

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** SQL query with CTEs and window functions
**Best Performer:** Claude AI

---

### Prompt 8
**Context:** Month-over-month analysis
**Prompt:**
> "Write a SQL query to calculate month-over-month revenue change using LAG window function. Table name: sales. Columns: sale_date, revenue. Show month, revenue, previous month revenue, and percentage change."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** SQL with LAG function and percentage calculation
**Best Performer:** ChatGPT

---

### Prompt 9
**Context:** Subquery for filtering
**Prompt:**
> "Write a SQL query to find all customers who have placed orders above the average order value. Use a subquery. Tables: customers (customer_id, name) and orders (order_id, customer_id, amount)."

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** SQL with subquery
**Best Performer:** GitHub Copilot

---

## Category 4: Data Visualisation

### Prompt 10
**Context:** Dashboard KPI design
**Prompt:**
> "I am building a Power BI dashboard for traffic analysis. Suggest 6 meaningful KPIs I should include, explain why each is important, and describe the best visual type for each KPI."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** List of KPIs with justification and visual recommendations
**Best Performer:** Claude AI

---

### Prompt 11
**Context:** Matplotlib chart customisation
**Prompt:**
> "Write Python code to create a professional-looking grouped bar chart using Matplotlib comparing weekday vs weekend traffic volume across 5 areas in Bengaluru. Add proper titles, labels, legend, and color scheme."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Clean Matplotlib code with customisation
**Best Performer:** Claude AI

---

### Prompt 12
**Context:** Seaborn heatmap
**Prompt:**
> "Write Python code to create a correlation heatmap using Seaborn for a DataFrame with columns: Traffic_Volume, Avg_Speed, Congestion_Level, Incidents, PT_Usage, Signal_Compliance. Add annotations and use a blue color palette."

**LLM Tested:** ChatGPT, Claude AI, GitHub Copilot
**Expected Output:** Seaborn heatmap code
**Best Performer:** GitHub Copilot

---

## Category 5: Statistical Analysis

### Prompt 13
**Context:** Hypothesis testing
**Prompt:**
> "Explain how to perform a t-test to check if there is a significant difference in average traffic volume between weekdays and weekends using Python (scipy.stats). Include code and interpretation of results."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** T-test explanation with code and interpretation
**Best Performer:** ChatGPT

---

### Prompt 14
**Context:** Regression analysis
**Prompt:**
> "Write Python code to perform simple linear regression to predict Congestion_Level based on Traffic_Volume using scikit-learn. Include train-test split, model training, prediction, and evaluation metrics (R2, MAE, RMSE)."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Complete regression code with evaluation
**Best Performer:** Claude AI

---

### Prompt 15
**Context:** Descriptive statistics
**Prompt:**
> "I have a sales dataset. Write Python code to generate a comprehensive descriptive statistics report including mean, median, mode, standard deviation, skewness, and kurtosis for all numerical columns. Export results to a CSV file."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Statistics code with CSV export
**Best Performer:** Claude AI

---

## Category 6: Business Insights

### Prompt 16
**Context:** Insight generation from data
**Prompt:**
> "Based on this summary: Koramangala has 94% average congestion, Silk Board experiences 43% speed reduction during 8-10 AM, and 57% of records show severe congestion. Generate 3 actionable business recommendations for Bengaluru traffic management."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** 3 clear, actionable recommendations
**Best Performer:** Claude AI

---

### Prompt 17
**Context:** Executive summary writing
**Prompt:**
> "Write a 200-word executive summary for a data analysis project on Bengaluru traffic patterns. Key findings: Koramangala is most congested, peak hours are 8-10 AM, fog increases incidents by 20%, roadwork increases congestion by 15%."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Professional executive summary
**Best Performer:** Claude AI

---

### Prompt 18
**Context:** Data storytelling
**Prompt:**
> "I need to present e-commerce sales analysis findings to non-technical stakeholders. Key data: Q3 revenue dropped 27%, cart abandonment is main cause, email campaigns can reduce churn by 15%. Help me structure a 5-slide presentation narrative."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Clear presentation structure with narrative
**Best Performer:** ChatGPT

---

### Prompt 19
**Context:** Anomaly explanation
**Prompt:**
> "In my monthly sales data, June shows a sudden spike of 815 units above the monthly average while July drops by 867 units. Generate 3 possible business explanations for this pattern and suggest how to investigate further."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Business explanations with investigation suggestions
**Best Performer:** Claude AI

---

### Prompt 20
**Context:** KPI interpretation
**Prompt:**
> "Explain the following KPIs in simple business terms for a non-technical audience: 1) Churn Rate, 2) Basket Size, 3) Profit Margin, 4) Congestion Index, 5) NRR (Net Revenue Retention). Keep each explanation under 50 words."

**LLM Tested:** ChatGPT, Claude AI
**Expected Output:** Simple, clear KPI explanations
**Best Performer:** Claude AI
