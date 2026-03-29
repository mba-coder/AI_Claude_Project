**AI Job Market Analysis using Claude**
The objective of this project was to analyze a large dataset of AI job market trends (10,000+ records) to understand the key factors influencing salaries, hiring demand, and skill requirements in the AI industry.
With the rapid growth of AI-related roles, there is a lack of clear, structured insights on:
What drives higher salaries in AI jobs
Whether skills or education have a greater impact on compensation
How experience levels influence pay
Whether remote roles offer better salary opportunities
What trends exist in hiring urgency and job demand
The goal was to transform raw, unstructured data into actionable insights that can help:
Job seekers understand how to position themselves
Analysts identify market trends
Businesses understand hiring patterns

**Business Question**
This analysis was driven by the following key questions:
What are the strongest drivers of salary in AI-related roles?
How do skills (Python, SQL, ML, Cloud) impact compensation?
Does education level significantly affect salary outcomes?
Are remote jobs paying more compared to on-site roles?
Which roles and experience levels are in highest demand? 

**Approach**
To solve this problem, I followed a structured data analysis workflow:
Dataset understanding and validation
Data cleaning and preprocessing
Feature engineering for better analysis
Exploratory Data Analysis (EDA)
Visualization and dashboard creation
Reporting and insight communication
AI (Claude) was used as a co-analyst to assist in executing tasks efficiently through structured prompt engineering, while all problem framing, validation, and interpretation were performed independently.

**Dataset Understanding (Context Setting)**
Prompt:
I am uploading a dataset with 10,000+ rows and multiple columns including job title, salary, skills, experience, and location. Before analysis, summarize the structure, identify data types, and flag potential data quality issues.
Purpose:
Understand dataset structure
Identify missing values and inconsistencies
Plan analysis approach 

**Role-Based Analysis**
Prompt:
Act as a senior data analyst with expertise in Job  market data. Help interpret findings, identify surprising patterns, and suggest insights suitable for a portfolio project.
Purpose:
Improve quality of insights
Get professional-level interpretation
Align output with real-world expectations 

**Data Cleaning (Task Decomposition)**
Prompt:
Write a Python data cleaning script using pandas with:
1. Load dataset
2. Null value checks for all columns
3. Duplicate detection
4. Outlier detection using 3-sigma rule
5. Data validation checks
Add comments for each step and keep the code beginner-friendly.

 **Feature Engineering (Output Control)**
Prompt:
Create new columns:
- skill_count (sum of all skill indicators)
- salary_band (Low, Mid, High, Top based on salary ranges)
Also include verification queries.
Purpose:
Add business-relevant features
Ensure correct implementation
Validate outputs

**Analytical Reasoning **
Prompt:
Given salary data across job roles, experience, and skills, reason step-by-step and rank the strongest factors influencing salary.Explain your reasoning before giving the final ranking.

** Dashboard Creation (Output Control + Iteration)**
Prompt (Initial):
Create an interactive dashboard with charts showing salary trends, skill distribution, and hiring demand.Use a dark theme and structured layout.
Refinement Prompt:
Improve the dashboard:
- Add KPI section
- Use specific color palette
- Add animations and hover effects
- Ensure clean layout
Purpose:
Build visualization structure
Improve design through iteration
Ensure professional output

**Report Generation **
Write a professional analyst report for a hiring manager reviewing a junior data analyst portfolio. Include insights, methodology, and structured findings.


** Key Learning**
AI is not a replacement for analysis — it is a multiplier of structured thinking. The quality of output depends on:
Clarity of prompts
Structure of tasks
Validation of results

** Conclusion**
This project demonstrates that effective use of AI in data analysis is not about automation, but about:
Designing the right prompts
Guiding AI through structured workflows
Interpreting and validating outputs
This approach reflects how modern data analysts can integrate AI into their workflow to improve efficiency and insight generation.







