# Reusable Prompt Library

## Overview
This is a curated collection of the best-performing prompts from the evaluation. These prompts consistently scored A+ (45+/50) across all LLMs and can be reused for similar tasks.

---

## 🔥 Data Analysis Prompts

### DA-001: Universal Data Cleaning Prompt
**Score: 49/50 | Best LLM: Claude AI**
```
I have a CSV dataset with [X] rows and [Y] columns. Some columns have missing values and duplicates. Write Python code using Pandas to:
1) Check for missing values and print a summary
2) Fill numeric columns with median
3) Fill categorical columns with mode
4) Remove duplicate rows
5) Print a before/after summary report
Dataset name: [dataset_name]
```

---

### DA-002: EDA Template Prompt
**Score: 49/50 | Best LLM: Claude AI**
```
I have a [domain] dataset with columns: [list columns]. Write Python code to perform complete EDA including:
1) Summary statistics for all columns
2) Distribution plots for numeric columns
3) Correlation heatmap
4) Top 5 [entity] by [metric]
5) [Time period] trend analysis
Save all plots as PNG files with descriptive names.
```

---

### DA-003: SQL CTE Prompt
**Score: 49/50 | Best LLM: Claude AI**
```
Write an optimised SQL query using CTEs to find [specific analysis].
Table: [table_name]
Columns: [list columns]
Requirements:
- Use CTEs for readability
- Include window functions where needed
- Add comments explaining each CTE
- Order results by [column] descending
```

---

### DA-004: Power BI KPI Design Prompt
**Score: 49/50 | Best LLM: Claude AI**
```
I am building a Power BI dashboard for [domain] analysis. Suggest [N] meaningful KPIs I should include. For each KPI provide:
1) KPI name
2) Why it is important for this business
3) How to calculate it
4) Best visual type (Card/Bar/Line/Gauge)
5) Target benchmark if applicable
```

---

## 🔥 Content Generation Prompts

### CG-001: LinkedIn Project Post Prompt
**Score: 50/50 | Best LLM: Claude AI**
```
Write a professional LinkedIn post announcing my [project name] project.
Include:
- 1-line project overview
- Tools used: [list tools]
- Key finding: [specific insight with number]
- What I learned
- Call to action (GitHub link or feedback request)
Keep under 200 words. Add 3-5 relevant emojis. Use line breaks for readability.
```

---

### CG-002: GitHub README Prompt
**Score: 49/50 | Best LLM: Claude AI**
```
Write a professional GitHub README for a project called '[project name]'.
Include these sections:
- Badges (Python, SQL, Power BI, Status)
- Overview (2-3 sentences)
- Problem Statement (bullet points)
- Dataset info (source, size, key features)
- Project structure (folder tree)
- Tools & Technologies (table)
- Key Findings (bullet points with numbers)
- How to Run (code blocks)
- Author section
Use markdown formatting throughout.
```

---

### CG-003: Professional Email Prompt
**Score: 50/50 | Best LLM: ChatGPT**
```
Write a professional email for [purpose].
Details:
- Recipient: [role/name]
- My background: [brief intro]
- Key points to cover: [list 3-4 points]
- Tone: [professional/friendly/formal]
- Word limit: under [X] words
- Include: subject line, greeting, body, closing
```

---

## 🔥 Coding Prompts

### CD-001: Reusable Function Prompt
**Score: 49/50 | Best LLM: GitHub Copilot**
```
Write a reusable Python function called '[function_name]' that:
1) Accepts [input parameters with types]
2) Performs [specific operations]
3) Returns [output with type]
4) Includes: docstring, type hints, error handling, and inline comments
5) Follows PEP 8 style guidelines
Include a usage example at the bottom.
```

---

### CD-002: Automated Script Prompt
**Score: 49/50 | Best LLM: Claude AI**
```
Write a Python script to automatically [task description].
Requirements:
- Input: [data source/format]
- Processing: [specific steps]
- Output: [format and location]
- Error handling: [specific scenarios]
- Logging: print progress messages
- Save output to [location] with [naming convention]
```

---

### CD-003: SQL Optimisation Prompt
**Score: 49/50 | Best LLM: Claude AI**
```
Review and optimise this SQL query for better performance:
[paste query]
Please:
1) Identify performance bottlenecks
2) Suggest index improvements
3) Replace subqueries with CTEs where beneficial
4) Provide optimised version with comments
5) Estimate performance improvement
```

---

## 📊 Prompt Engineering Best Practices

Based on 50+ prompt evaluations, here are the key findings:

### 1. Be Specific
❌ "Write code to clean data"
✅ "Write Python code using Pandas to clean a 15,000 row CSV by removing duplicates, filling nulls with median, and printing a summary report"

### 2. Provide Context
❌ "Write a SQL query for top roads"
✅ "Write a SQL query using CTEs to find top 5 most congested roads. Table: traffic. Columns: road, area, congestion_level, date"

### 3. Specify Output Format
❌ "Explain RFM analysis"
✅ "Explain RFM analysis with Python code, include a table showing score ranges, and save results to CSV"

### 4. Set Constraints
❌ "Write a LinkedIn post"
✅ "Write a LinkedIn post under 200 words with 3 emojis and a call to action"

### 5. Request Examples
❌ "Explain window functions"
✅ "Explain SQL window functions with 3 practical examples using a sales table"

---

## 🏆 LLM Performance Summary

| Task Category | Best LLM | Average Score |
|---------------|----------|---------------|
| Data Analysis | Claude AI | 48.2/50 |
| SQL Queries | Claude AI | 47.5/50 |
| Code Generation | GitHub Copilot | 47.8/50 |
| Content Writing | Claude AI | 48.5/50 |
| Email Writing | ChatGPT | 49.0/50 |
| Code Debugging | GitHub Copilot | 48.0/50 |

**Overall Winner: Claude AI** — best for analytical and content tasks
**Runner Up: GitHub Copilot** — best for pure code generation
