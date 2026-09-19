# AI Prompt Evaluation & Response Quality Assessment

![Python](https://img.shields.io/badge/Python-3.10-blue) ![LLM](https://img.shields.io/badge/LLM-Prompt%20Engineering-purple) ![ChatGPT](https://img.shields.io/badge/ChatGPT-Tested-green) ![Claude](https://img.shields.io/badge/Claude%20AI-Tested-orange) ![Copilot](https://img.shields.io/badge/GitHub%20Copilot-Tested-lightgrey) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Overview

A comprehensive prompt engineering project evaluating AI-generated responses across three major LLM platforms — ChatGPT, Claude AI, and GitHub Copilot. The project covers 50+ prompts across data analysis, content generation, and coding tasks, scored using a structured 5-parameter rubric.

---

## Problem Statement

As AI tools become mainstream in data and tech roles, the ability to craft effective prompts and evaluate AI outputs becomes a critical skill. This project aims to:
- Design high-quality prompts for real-world data analysis tasks
- Evaluate AI responses using a structured scoring rubric
- Compare LLM performance across different task categories
- Build a reusable prompt library for data analysts

---

## Project Structure

```
ai-prompt-evaluation/
├── prompts/
│   ├── data_analysis_prompts.md       # 20+ data analysis prompts
│   ├── content_generation_prompts.md  # 15+ content generation prompts
│   └── coding_prompts.md              # 15+ coding prompts
├── evaluations/
│   └── evaluation_results.csv         # Scored results for all prompts
├── scoring/
│   └── scoring_rubric.md              # 5-parameter evaluation rubric
├── prompt_library/
│   └── reusable_prompts.md            # Best-performing prompt templates
└── README.md
```

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| ChatGPT (GPT-4) | LLM testing and evaluation |
| Claude AI | LLM testing and evaluation |
| GitHub Copilot | Code generation evaluation |
| Structured Rubric | Response scoring (5 parameters) |
| Python | Data analysis prompt testing |
| SQL | Query generation prompt testing |

---

## Scoring Rubric

Each AI response is scored on 5 parameters (0-10 each):

| Parameter | Description |
|-----------|-------------|
| Accuracy | Factual correctness of response |
| Relevance | How well it addresses the prompt |
| Tone & Style | Appropriateness for context |
| Coherence | Structure and logical flow |
| Completeness | Coverage of all required points |

**Maximum Score: 50 | Grade A+: 45-50**

---

## Key Findings

- **Claude AI** performed best for data analysis, SQL, and content writing tasks
- **GitHub Copilot** excelled in pure code generation tasks
- **ChatGPT** was strongest for email writing and RFM analysis
- Prompts with specific context and constraints scored 20% higher than vague prompts
- Adding output format requirements improved response quality significantly
- 78% of all evaluated responses scored A or above (38+/50)

---

## LLM Performance Summary

| Task Category | Best LLM | Avg Score |
|---------------|----------|-----------|
| Data Analysis | Claude AI | 48.2/50 |
| SQL Queries | Claude AI | 47.5/50 |
| Code Generation | GitHub Copilot | 47.8/50 |
| Content Writing | Claude AI | 48.5/50 |
| Email Writing | ChatGPT | 49.0/50 |

---

## Prompt Engineering Best Practices

1. **Be Specific** — include exact column names, dataset sizes, and expected outputs
2. **Provide Context** — explain the business problem, not just the technical task
3. **Set Constraints** — specify word limits, format requirements, and style
4. **Request Examples** — ask for code examples and usage demonstrations
5. **Iterate** — refine prompts based on initial outputs for better results

---

## How to Use This Repository

1. Browse `prompts/` folder for task-specific prompt templates
2. Use `scoring/scoring_rubric.md` to evaluate any AI-generated response
3. Check `evaluations/evaluation_results.csv` for benchmark scores
4. Use `prompt_library/reusable_prompts.md` for ready-to-use templates

---

## Author

**Akshobhya Pranesh Pappu**
MCA Final Year | NMIT Bengaluru | Aspiring Data Analyst & Prompt Engineer
[GitHub](https://github.com/Akshobhya118) | akshobhya2003@gmail.com

---

## License

This project is open source and available under the [MIT License](LICENSE).
