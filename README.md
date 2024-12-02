
# Workplace Attendance Analysis Dashboard in Power BI
![Alt text](hr-analytics.webp)

## Objective
To analyze workforce attendance patterns and trends, enabling data-driven decision-making to enhance workforce management and operational efficiency.

## Dataset Overview
- **Source**: Internal CRM data (April 2022 - July 2022).  
- **Key Attributes**: Employee Code, Employee Name, Date, Attendance Status.  
- **Preprocessing**:  
  - Transformed the date column from a columnar format into a row-wise setup for easier analysis.  
  - Consolidated data from three separate sheets into a unified dataset.  
  - Created calculated metrics for tracking KPIs such as attendance rates and leave categories.

## Key Features
1. Designed an interactive dashboard showcasing:  
   - Staff Presence Percentage.  
   - Remote Work Percentage.  
   - Sick Leave Percentage.  
   - Total Working Days.  
2. Leveraged DAX for calculated columns and measures, including:  
   - **Work From Home Count**.  
   - **Month and Year Extraction**.  
   - **Sick Leave Count**.  
   - **Day of the Week Identification**.

## Tools and Techniques
1. **Power BI Desktop**: For dashboard design and data visualization.  
2. **Advanced DAX**: For creating dynamic calculated columns and measures.  

## Insights Derived
1. Staff presence over the analyzed period averaged **91.55%**.  
2. **11.15%** of the workforce engaged in remote work.  
3. **1.18%** of employees were unavailable due to sick leave.  
4. Attendance Trends:  
   - **April 2022** recorded the highest attendance rate at **94%**, while **May 2022** had the lowest at **89%**.  
   - **Tuesdays** consistently showed the highest attendance, while **Fridays** recorded the most remote work activity.  
5. Outlier Observation:  
   - *Gregory Carr*, a fully remote employee, was only present **52.38%** of the time, highlighting a performance concern that requires further review.

## Outcome and Value
The dashboard provided actionable insights into attendance patterns, helping HR and management to:  
- Address attendance and productivity gaps.  
- Refine remote work policies.  
- Optimize workforce planning based on day-wise trends.
