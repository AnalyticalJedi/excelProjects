# Job Applications Analysis 2019

## Overview
This project analyzes job applications submitted to a recruiting agency's online platform in 2019. The goal is to provide insights into application trends, helping optimize the agency's online application process.

## Objective
The project answers the following business questions:
1. **Total applications received per month in 2019.**
2. **Months with the least and greatest number of applications.**
3. **Average number of applications received per month.**

## Tools Used
- **Spreadsheet Software (Excel/Google Sheets):**
  - Data Cleaning (Sorting and Formatting)
  - Functions: `TEXT`, `COUNTIF`, `SUM`, `MIN`, `MAX`, `AVERAGE`
  - Data Table Creation
- **Visualization:**
  - Bar chart for monthly application totals (Excel/Python).

## Process
1. **Data Preparation:**
   - Imported raw data and sorted by date.
   - Created a new column to extract month names using the `TEXT` function.

2. **Data Aggregation:**
   - Built a custom data table to calculate monthly application totals using the `COUNTIF` function.

3. **Summary Statistics:**
   - Total applications in 2019: **32,595**
   - Peak month: **July** (3,138 applications)
   - Slowest month: **February** (2,312 applications)
   - Average monthly applications: **2,716**

4. **Visualization:**
   - Created a bar chart to display monthly application totals.

## Insights
- **Peak Period:** July saw the highest applications, indicating strong demand.
- **Slow Period:** February had the least applications, presenting an opportunity to increase advertising efforts.
- **Strategic Impact:** Data analysis helps allocate resources effectively for advertising and outreach.

## Files
- `Data/`
  - `2019_data_analyst_jobs.xlsx`: Raw and summary data.
- `Visuals/`
  - `Monthly_Applications_2019.png`: Bar chart of monthly application totals.

## How to Use
1. Open the `2019_data_analyst_jobs.xlsx` file to explore raw and summary data.
2. Review the visual representation in the `Monthly_Applications_2019.png` file.
3. Use the insights to inform decisions regarding recruitment strategies.

## Next Steps
- Extend analysis to other years for comparative trends.
- Explore more advanced visualizations using Tableau or Python.

## Contact
For questions or feedback, please reach out via email or LinkedIn.
