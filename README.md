# HealthCare-Analytics-Dashboard
This dashboard will give Hospital Staff detail information about what is the issue and what all steps they should be taking to solve those issue with the help of Data Analytics. 


# Project Title

**A brief description of this project**

This comprehensive Healthcare Analytics Dashboard is designed to provide healthcare professionals and administrators with insights into patient visits, treatment satisfaction, waiting times, and demographic distributions. The dashboard helps to understand patient flow, identify areas for improvement, and enhance overall patient care.

Using **Power BI, DAX Functions, and Power Query**, organizations can visualize key healthcare metrics such as Total patient visits, average satisfaction, average waiting time, age group distribution, yearly trends, monthly visits, etc. They can also analyze historical data to identify trends, optimize operations, and make informed decisions to improve efficiency and reduce waiting time, and provide the best facilities to the patients.

# Healthcare Analytics Dashboard

### Dashboard Link : 

**https://app.powerbi.com/groups/me/reports/6798e87c-11ef-4efd-9241-aee0799e1316/9a213e260d02260ed8b7?experience=power-bi**

## Problem Statement

In the fast-paced environment of healthcare, administrators and professionals often struggle to effectively monitor and analyze critical patient metrics such as visit counts, waiting times, treatment satisfaction, and demographic distributions. This lack of comprehensive and easily accessible data can hinder the ability to make informed decisions, optimize patient flow, improve service delivery, and enhance overall patient care.

### Summary for Steps followed 
1. **Collecting Data**
**Data Source**: The data for this project was collected from hospital records, patient feedback forms, and internal healthcare systems.

2. **Loading Data into Power BI**
**Data Import**: The data was imported into Power BI using CSV files and database connections.

3. **Checking Data in Power Query Editor**
**Data Review**: In Power Query Editor, we examined the data to understand its structure and identify any inconsistencies.
Full Data Visibility: Ensured that Power BI could display the entire dataset by adjusting settings as needed.

4. **Data Cleaning**
**Cleaning Process**: Addressed missing values, corrected errors, and standardized data formats to ensure accuracy and usability.

5. **Data Manipulation and Measures Creation**
**Data Manipulation**: We performed various data manipulation tasks to transform and reshape the data as needed. This included filtering, grouping, and aggregating data to prepare it for detailed analysis.

**Creating Measures**: Using DAX (Data Analysis Expressions), we created multiple measures to facilitate our analysis. 

**Some of the key measures included**:

a. Total Visits = COUNT([VisitID]).

b. Average Waiting Time = AVERAGE([WaitingTime]).

c. Satisfaction Rate = CALCULATE(AVERAGE([SatisfactionScore]), FILTER([SatisfactionScore] >= 4)).

d. Referral Percentage = DIVIDE(CALCULATE(COUNT([PatientID]), [Referred] = "Yes"), COUNT([PatientID])).

6. **Data Visualization**
**Creating Visuals**: Developed various charts and graphs in Power BI to visualize key metrics and insights.

**Visual Enhancements**: Applied themes, colors, and labels to make the dashboard intuitive and visually appealing.


# Report Snapshot (Power BI DESKTOP)
![image](https://github.com/MithilKothari/HealthCare-Analytics-Dashboard/assets/156261969/18b0f9cd-56a4-4c17-890f-fef1e2266bcd)




