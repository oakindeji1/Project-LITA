# Project-LITA
# HR Analytics Employee Attrition &amp; Performance
## Overview
This project collects and analyses the factors that lead to employee attrition and explore important questions.

## Data Collected
- The dataset includes the following key columns:

1 Education ('Below College', 'College','Bachelor','Master','Doctor')
  
2 EnvironmentSatisfaction ('Low','Medium', 'High','Very High') 

3 JobInvolvement ('Low', 'Medium' ,'High', 'Very High')

4 JobSatisfaction ('Low','Medium','High','Very High')

5 PerformanceRating ('Low','Good','Excellent','Outstanding')

6 RelationshipSatisfaction ('Low','Medium','High','Very High')

7 WorkLifeBalance ('Bad','Good','Better','Best')

## Project Objectives
This project was designed to address the following analysis goals:

## Employee Attrition Analysis
### Objective: Identify factors related to employee attrition (i.e., why employees leave).
### Approach:
- Use Pivot Tables to analyze attrition rates across different departments, job roles, and demographics.
- Calculate attrition percentage by filtering the Attrition column, and then check for patterns based on age, gender, department, and job role.
## Employee Satisfaction and Engagement Insights
### Objective: Evaluate levels of job satisfaction, environment satisfaction, and work-life balance.
### Approach:
-Use Average and Count functions on satisfaction-related columns (e.g., JobSatisfaction, EnvironmentSatisfaction, WorkLifeBalance).
Conditional Formatting can visually highlight satisfaction levels across different departments or roles, helping to identify areas where improvements may be needed.
## Compensation and Benefits Analysis
### Objective: Analyze salary distribution and its relationship to job levels, roles, or performance ratings.
### Approach:
- Use Charts (e.g., bar charts, box plots) to display MonthlyIncome and HourlyRate distributions.
- Create Pivot Tables to compare income levels across different JobLevels and JobRoles.
- Evaluate the StockOptionLevel and PercentSalaryHike columns to see if these factors influence employee retention.
## Demographic Analysis
### Objective: Understand workforce composition in terms of age, gender, education, and department.
### Approach:
- Generate Demographic Profiles by analyzing columns such as Age, Gender, Education, and Department.
- Use Charts (e.g., pie charts, histograms) to visualize age distribution and departmental gender ratios.
- Pivot by EducationField to understand the educational backgrounds of your workforce and how these relate to job roles or satisfaction.
## Work Experience and Tenure Analysis
### Objective: Assess employee tenure, promotion frequency, and career progression.
### Approach:
- Calculate averages for YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion, and YearsWithCurrManager to get insights into employee tenure.
- Pivot and filter by Attrition to see if shorter tenures correlate with higher turnover.
- Use Charts to illustrate the typical career progression (e.g., time between promotions or average years in current role) to help plan development initiatives.
## Travel and Work-life Balance Analysis
###Objective: Evaluate how travel frequency impacts employee satisfaction and attrition.
###Approach:
- Use Pivot Tables to assess BusinessTravel frequency against Attrition and WorkLifeBalance.
- Analyze the correlation between BusinessTravel and job satisfaction, tenure, or other retention indicators.
## Performance and Productivity Analysis
### Objective: Examine factors associated with high-performing employees and those who received salary hikes.
### Approach:
- Filter by PerformanceRating and use Pivot Tables to analyze the distribution of high ratings across different departments or job roles.
- Use Correlation Analysis (with Excel’s CORREL function) to examine relationships between PerformanceRating, JobInvolvement, and PercentSalaryHike.
## Predictive Trend Analysis (Basic)
### Objective: Identify trends and create basic predictive insights on factors impacting attrition.
### Approach:
- Use Scatter Plots to see if there are linear relationships between attrition and key variables like age, income, or years at the company.
- Use Trendlines in scatter plots to explore the relationship strength, helping you understand potential predictors of attrition.


How to Use the Data
Revenue by Region: Group the data by region and sum the revenue column. This provides an overview of how much revenue each region is generating.

Units Sold by Region: Group the data by region and sum the units sold to identify which regions are moving the most products.

Average Revenue by Region: To get the average revenue per transaction or unit sold in a region, use the formula:

Formula Used
Average Revenue = Total Revenue / Units Sold
Tools and Methods Used
Data Analysis: The data was analyzed using Microsoft Excel, utilizing Pivot Tables to organize, summarize, and filter the data for easier interpretation.

Data Visualization: Bar Charts were created in Excel to visually represent the key insights.
