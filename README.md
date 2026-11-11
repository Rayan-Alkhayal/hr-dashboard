# HR Dashboard (Power BI)

**An interactive Power BI dashboard that turns 970 employee records into clear insights on headcount, salary, performance, leaves, and training.**

Built with Power BI Desktop, Power Query, and DAX.

![Dashboard Preview](images/dashboard.png)

## Highlights
- **Power Query:** loaded from Excel and removed 25 rows (2.5%) with null, blank, or "Unknown" values (995 to 970 records)
- **DAX:** 6 measures (Total Salary, Avg. Performance Score, Total Leaves, Total Overtime, Total Training Hours, Total Promotions)
- **Field parameters:** switch the measure shown by department, and the chart dimension (department or position), with one click
- **Interactive layout:** 5 KPI cards, a branch slicer, 5 charts, and a department-by-position matrix on a custom 1920x1080 page

## Key Insights
- 970 employees; 55% female; education levels are evenly spread (Bachelor's 26%, Master's 26%, High School 26%, PhD 22%).
- HR is the largest department (18%) and has the most leave days (2,754 of 14,454).
- Employees joined at a rate of 97 to 132 per year (2015-2022), with the lowest in 2020.
- Average performance score is 2.97 out of 5, and average training is 19.2 hours per employee.

## Dataset
Training dataset provided by the instructor of a data analysis training program, shared with permission. The original file is in the `data` folder.

## How to Use
1. Download [hr-dashboard.pbix](hr-dashboard.pbix) and open it in Power BI Desktop (Windows).
2. Use the branch slicer and the two field-parameter slicers to explore the data.
