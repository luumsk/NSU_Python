# Projects

## 1. Python

#### 1.1. Description

Write a to-do list small application applying Object Oriented Programming. The to-do list must have these following abilities:

- **add task**: add new task to the list. A task must contain these following attribute:
    - id (required)
    - title (required)
    - description
    - created_date (required)
    - tags
- **get all tasks**: return all tasks in the list
- **get a task**: return a task by task id
- **remove task**: remove a task from a list by a task_id
- **filter tasks by date**: get a list of tasks created on a date or created in a period of time. For example, get all tasks created on 20.09.2023, or get all tasks created from 20.09.2023 to 27.09.2023
- **filter tasks by tag/tags**: get a list of tasks that are marked with the query tag.

#### 1.2. Requirements
- All methods mentioned above must be implemented.
- Follow OOP concepts.
- Handling exceptions with clear messages return if errors or task not found.
- Documenting: Write docstrings or a separate document to explain how to use your to-do list.
- Database: You can use any form of database, a CSV/JSON/TXT file or a small database to store your data.

Format of submisison: Github repo or a jupyter notebook

#### 1.3. How do I test your work?
- Based on your document, I will test all required methods.
- I might test 1-2 unusual cases.
- I will ask 1-3 questions regarding your code.


### 2. Data Analysis and Visualization with Python

#### 2.1. Description
The file `data/data.csv` contains salary trends in the field of data in the period 2021 - 2023, including these fields:

- `work_year`: the year when the salary data was collected.
- `experience_level`: EN (Entry-Level), EX (Experienced), MI (Mid-Level), SE (Senior).
- `employment_type`: FT (Full-Time), CT (Contractor), FL (Freelancer), PT (Part-Time).
- `job_title`: "Applied Scientist", "Data Quality Analyst", etc.
- `salary`: The salary figures in their respective currency formats.
- `salary_currency`: The currency code representing the salary.
- `salary_in_usd`: The converted salary figures in USD.
- `company_location`: The location of the companies, specified as country codes (e.g., "US" for the United States and "NG" for Nigeria).
- `company_size`: "L" (Large), "M" (Medium), and "S" (Small).

#### 2.2. Requirements

Your task is to validate the quality of data, analyse data , and visualize the findings:

- Validate quality: Is there any missing values? If yes, handle the missing values. Are all categorical data uniform etc.

- Analyze data:
    - Pick any 5 fields in the dataset and present to me what you found by analysing each individual field, for example, central tendency, outliers
    - Combine at least 2 pairs of fields and tell me what you found, for example, correlation between 2 fields
    - Answering this question: If I am an experienced level Data Scientist looking for a full-time job in a small size company in Europe, in term of salary, which are the top 3 countries I should aim for?

- Visualization:
    - Plot at least 1 histogram, 1 pie chart, and 1 bar chart.

Format of submisison: Github repo or a jupyter notebook

#### 2.3. How do I test your work?

- The purpose of this test is to evaluate your ability to use Python as a tool for data manipulation and visualization, the quality of the analysis findings will not be graded, but extra point for creativity findings.
- I will check your work of data manipulation, your analysis and visualization. Your work must contain the minimum requirements and you must answer the analysis question above correctly.
- I will ask you 1-2 questions regarding your work.

**DEADLINE**: **10:50 GMT+7 on Thursday, 02.11.2023**
