# 📊 Data Professional Survey Breakdown – Power BI Dashboard

## 📌 Project Overview

This project focuses on analyzing a survey conducted among data professionals to understand current trends and patterns within the data science and analytics industry.

The survey explores different aspects of professionals' careers, including their job roles, salaries, geographical locations, favorite programming languages, work-life balance, salary satisfaction, and opportunities to learn new skills.

The primary objective of this project is to transform raw survey data into meaningful insights through data cleaning, transformation, analysis, and interactive visualization using Microsoft Power BI.

## 🎯 Problem Statement

The data industry consists of various career paths, including Data Analysts, Data Scientists, Data Engineers, Data Architects, and Database Developers.

However, understanding the trends and preferences of professionals across these roles can be challenging without properly analyzing the available data.

This project aims to answer questions such as:

- Which programming languages are most popular among data professionals?
- Which job roles offer higher average salaries?
- How do salaries vary across different professional roles?
- Which countries have the highest representation in the survey?
- How satisfied are professionals with their salaries?
- How do professionals rate their work-life balance?
- How difficult is it for professionals to break into the data industry?
- How do professionals feel about learning new skills?

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – Dashboard development and data visualization.
- **Microsoft Excel** – Initial data inspection and preparation.
- **Power Query Editor** – Data cleaning, transformation, and standardization.
- **DAX** – Calculations and aggregations for dashboard metrics.

## 📂 Project Workflow

### 1. Data Import

- Imported the survey dataset from Microsoft Excel into Power BI.
- Inspected the dataset to understand its structure, columns, and data types.
- Identified unnecessary columns and fields that required transformation.

### 2. Data Cleaning & Transformation

Used Power Query Editor to clean and prepare the raw survey data.

**Step 1: Remove Unnecessary Columns**

- Removed irrelevant columns that were not required for the analysis.
- Retained the relevant survey responses for dashboard development.

**Step 2: Standardize Job Titles**

The survey question *"Which title best fits your current role?"* contained multiple job titles and variations under the "Other" option.

To standardize the data:

- Created a duplicate of the original job title column.
- Used the **Split Column by Delimiter** feature to separate the relevant information.
- Removed unnecessary split columns.
- Standardized the different variations into the appropriate categories, including "Other".

**Step 3: Standardize Other Survey Responses**

Applied a similar transformation process to the following columns:

- Country of residence.
- Favorite programming language.
- Industry of employment.

This helped maintain consistent categories and avoid duplicate or inconsistent responses during analysis.

**Step 4: Salary Data Transformation**

The original salary column contained salary ranges rather than individual numerical values.

To make the salary information suitable for numerical analysis:

- Created duplicate columns from the original salary column.
- Used **Split Column by Delimiter** to separate the lower and upper salary ranges.
- Removed unnecessary columns.
- Checked and cleaned both split columns to extract numerical values.
- Replaced additional symbols such as `+` and other non-numeric characters with appropriate numerical values.
- Created a new calculated column to determine the average salary using the lower and upper salary values.

This allowed salary information to be analyzed using numerical aggregations and comparisons.

**Step 5: Apply Transformations**

- Reviewed the cleaned columns and data types.
- Applied all transformations in Power Query.
- Loaded the transformed dataset into Power BI for visualization.

### 3. Dashboard Development

Created an interactive dashboard to present the survey findings through different visualizations.

The dashboard includes the following components:

| Visualization | Purpose |
|---|---|
| Average Salary by Job Title | Compares average salaries across different professional roles. |
| Survey Participants by Country | Displays the geographical distribution of survey participants. |
| Count of Survey Participants | Shows the total number of survey respondents. |
| Average Age of Survey Takers | Displays the average age of participants. |
| Work-Life Balance Satisfaction | Measures how professionals rate their work-life balance. |
| Happiness with Salary | Evaluates overall salary satisfaction. |
| Favorite Programming Language | Identifies the most preferred programming languages among professionals. |
| Difficulty to Break into Data | Analyzes how difficult participants find entering the data industry. |
| Happiness with Learning New Skills | Explores professionals' perspectives on learning and developing new skills. |

## 📈 Key Insights & Findings

Based on the dashboard analysis, several interesting patterns can be observed:

**1. Programming Language Preferences**
- Python is the most popular programming language among survey participants.
- Other languages, including R, C/C++, JavaScript, and Java, have comparatively lower representation.
- This highlights Python's strong presence in the data profession.

**2. Average Salary by Job Title**
- Data Scientists have the highest average salary among the displayed job categories.
- Data Engineers and Data Architects also demonstrate relatively high average salaries.
- Database Developers and professionals in entry-level or other categories show comparatively lower average salaries.

**3. Geographical Distribution**
- Survey participants come from different countries, including Canada, India, the United States, and the United Kingdom.
- The dashboard also includes participants grouped under "Other".

**4. Work-Life Balance**
- The average work-life balance satisfaction score is **5.74 out of 10**.
- This indicates a moderate satisfaction level among survey participants.

**5. Salary Satisfaction**
- The average happiness with salary score is **4.27 out of 10**.
- This suggests that salary satisfaction is relatively low among the respondents.

**6. Difficulty of Entering the Data Industry**
- Approximately 42.7% of participants consider entering the data industry neither easy nor difficult.
- Around 24.76% find it difficult.
- Approximately 21.27% find it easy.
- A smaller percentage consider it very difficult or very easy.

These findings provide an overview of the challenges and experiences reported by professionals working in the data industry.

## 📷 Dashboard Preview

The Power BI dashboard provides a consolidated view of the survey findings, allowing users to explore different aspects of the data profession.

<img width="1196" height="673" alt="Screenshot 2026-11-25 161433" src="https://github.com/user-attachments/assets/61c13305-6b01-4867-8de7-20c3ed5745a1" />

## 💡 Skills Demonstrated

Through this project, I demonstrated practical skills in:

- Data Importing and Preparation
- Data Cleaning and Standardization
- Power Query Transformations
- Splitting Columns Using Delimiters
- Handling Text-Based Salary Ranges
- Creating Calculated Columns
- Data Aggregation and Analysis
- Data Visualization
- Dashboard Design
- Business Intelligence and Insight Generation

## 📝 Conclusion

This project demonstrates how raw survey data can be transformed into meaningful information through data cleaning, transformation, and visualization.

By analyzing the responses of 630 survey participants, the dashboard provides insights into salary trends, programming language preferences, geographical distribution, career challenges, and job satisfaction within the data profession.

It also highlights the importance of data analytics and business intelligence in identifying patterns and supporting data-driven decision-making.

---

**Project Type:** Data Analytics | Business Intelligence

**Tool:** Microsoft Power BI

**Dataset:** Data Professional Survey

**Author:** Rajeshwaran Abiraj
