# HR-Dashboard-Report
A dynamic Power BI HR Dashboard visualizing employee demographics, tenure, performance, and work patterns.

## Project Purpose & Business Value
The primary purpose of this dashboard is to enable management to gain deep insights into workforce data through interactive visualizations, supporting informed and strategic decision-making. It visualizes key HR indicators such as total employees, gender distribution, years of service, job satisfaction levels, distance between employees’ homes and the office, overtime status, marital status, education fields, and more.

These insights help leaders identify which employees may deserve bonuses, reevaluate the performance of underperforming staff, and take initiatives such as providing transportation support for employees living far from the office.

The project uses a simulated dataset with 1,470 rows and 43 columns, enhanced with additional calculated columns for better data interpretation. DAX formulas and conditional formatting were applied to create more meaningful and intuitive visuals. Ultimately, this dashboard empowers HR teams and management to better understand the workforce and make data-driven decisions.

## About the Dataset & Key Metrics
This project uses a simulated dataset containing 1,470 rows and 43 columns. During visualization, additional calculated columns were created using DAX to make the analysis more insightful and easier to interpret.

The dashboard highlights key HR metrics through the following visuals:

- Total Employees – a card visual showing the overall workforce size
- Male Employees – a card visual showing the total number of male employees
- Female Employees – a card visual showing the total number of female employees
- Service Years – a clustered bar chart displaying employee tenure distribution
- Distance Status – a donut chart showing employees grouped by the distance between their home and office
- Job Levels – a stacked column chart illustrating five job levels based on satisfaction levels
- Overtime Status – a pie chart comparing employees working overtime vs. not
- Employees Job Satisfaction – a stacked column chart dividing job satisfaction into high, medium, and low categories
- Employees Indicators by Education Fields – a clustered column chart displaying employees categorized by their education fields
- Travel Status – a pie chart showing the proportion of employees who travel for work
- Employees Marital Status – a clustered column chart grouping employees by marital status

The dashboard consists of multiple pages with page navigation for seamless transitions. Users can also apply slicers and filters to explore specific segments of the workforce in greater detail.

## Technical Implementation
This dashboard was developed in Power BI using several technical approaches to enhance data analysis and usability:

1. DAX formulas: Core DAX functions such as COUNTROWS, CALCULATE, and DIVIDE were used to perform calculations and derive percentage metrics.
2. Creation of additional columns: Conditional formatting was applied to generate new calculated columns, making visuals more intuitive and easier to interpret.
3. Page Navigation: The dashboard consists of multiple pages with page navigation implemented for seamless transitions between views.
4. Visual design and structuring: Card visuals were used for KPIs, clustered/stacked bar and column charts for comparisons, and donut/pie charts for ratio-based insights.
5. Interactive user experience: Users can explore data more deeply through interactive filtering and visual-level cross-highlighting.

These technical implementations allow management to make more informed and visually supported decisions about the workforce.

## Dashboard Preview
![Home Page](https://github.com/seymurabdullayev/HR-Dashboard-Report/blob/d266d1aad6a2e2101fd298f5e1ecec8a405257c1/Home%20Page%20.png)

![Detail Page](https://github.com/seymurabdullayev/HR-Dashboard-Report/blob/d266d1aad6a2e2101fd298f5e1ecec8a405257c1/Detail%20Page.png)

![Action Page](https://github.com/seymurabdullayev/HR-Dashboard-Report/blob/d266d1aad6a2e2101fd298f5e1ecec8a405257c1/Action%20Page.png)
