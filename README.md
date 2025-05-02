📝 Project Overview
This HR Dashboard provides a comprehensive view of workforce analytics using interactive Power BI visuals. It is designed to support HR decision-making with insights into employee demographics, performance, retention risks, and workforce planning.

🔍 Key Features and Insights
Gender Distribution

Percentage breakdown of male and female employees.

Visualized for quick representation.

Promotion Eligibility

Categorizes employees as:

Due for Promotion

Not Due for Promotion

Calculated using DAX based on tenure or performance criteria.

Performance Ratings

Identifies:

High-performing employees

Low-performing employees

Useful for performance management reviews.

Retirement Readiness

Employees segmented by:

Due for Retirement

Not Due for Retirement

Helps in succession planning and risk analysis.

% Insights

All major KPIs like gender ratio, promotion rate, performance rating, etc., presented as percentage cards for quick snapshot understanding.

Distance Status

Shows the physical or commute distance status of employees from the workplace.

Could help in relocation, travel support, or hybrid work decisions.

Job Satisfaction

Employee sentiment or job satisfaction score visualized.

Helps monitor engagement and morale trends.

🛠️ Technical Details

Data Source: (Excel)

DAX Measures Used:

Gender % = (COUNT of Male/Female) / Total Employees

Promotion Status = IF logic based on tenure/performance

Retirement Flag = IF age >= retirement threshold

Other calculated columns/measures for KPI cards

Slicers/Filters:

Department

Job Role

Age Group

Performance Rating

📌 Use Cases
Identify promotion-ready employees.

Analyze diversity and gender balance.

Flag retirement risks for workforce planning.

Monitor satisfaction to improve retention.
