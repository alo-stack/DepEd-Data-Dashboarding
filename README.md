# DepEd-Data-Dashboarding
A data visualization and analysis project centered on the Department of Education (DepEd) 2024 enrolment data.
# Project Overview
With the recent change in administration, the Department of Education (DepEd) is prioritizing a deeper understanding of the Philippine education system. A crucial element in this effort is the analysis of annual enrolment data gathered through the Learner Information System (LIS).
However, the current system lacks a real-time dashboard, relying instead on manual data extraction for analysis. To support more efficient, data-driven decision-making, this project focuses on:

- Cleaning and processing enrolment data using Python’s Pandas library

- Developing an interactive dashboard to visualize key enrolment metrics

- Enabling filters by geographical areas and school attributes for intuitive data exploration
# Dataset Structure
The enrollment database structure comprises 67 columns and contains a total of 60,172 records.

- Privacy Notice: In compliance with data privacy regulations, the enrollment dataset used in this project is confidential and cannot be publicly shared or distributed.
# Work Highlights
Data Cleaning (Python)

* Removed irrelevant rows to ensure dataset relevance
* Replaced null values with `"Not Applicable"` instead of dropping rows to retain important data
* Detected and removed duplicate entries to uphold data integrity
* Cleaned invalid inputs such as `"n/a"` and empty strings
* Dropped columns with high levels of missing data that had little impact on the dashboard
* Standardized data formatting for consistency:

  * Converted text to uppercase
  * Resolved inconsistent abbreviations
  * Removed unnecessary punctuation
* Reshaped the dataset from wide to long format for improved analysis
* Exported the cleaned data with proper encoding to handle special characters
* *See full data cleaning breakdown \[here]*

**Data Verification (Excel)**

* Used pivot tables and slicers in Excel to cross-validate computed values used in Plotly Dash and Tableau

**Dashboard Development (Plotly Dash & Tableau)**

* Developed an interactive dashboard enabling DepEd personnel to:

  * Effortlessly explore and interpret enrollment trends
  * Apply filters for more informed education program and policy planning
# Dashboard Preview
