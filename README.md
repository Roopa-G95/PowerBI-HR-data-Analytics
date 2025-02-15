
# HR Analytics Dashboard: Enhancing Workforce Insights and Decision-Making

## Problem Statement
HR department is responsible for monitoring and managing various aspects of employee data to ensure the organization maintains a healthy Workforce.Due to lack of clear performance indicators and visualizations the HR department faces challenges in monitoring and analyzing employee data.
Attrition metrics are not standardized, making it difficult to track turnover, compare with benchmarks and evaluate engagement.

There is no visualization for demographic insights, attrition by gender,department or education field,preventing tailored interventions.Additionally job satisfaction ratings are not measured effectively,limiting efforts to improve employee engagement. 
These gaps hinder effective decision-making and workforce management.

### Steps Followed in PowerBI

1.Data Loading: The dataset is loaded in the powerbi desktop, the data set is in CSV format

2.Data Profiling: Then first row of the table is reviewed to determine whether it contains headers or data values. If the first row is identified as data, the "Use first row as headers" option is selected. Additionally, columns are examined for any missing or inconsistent values.

Text to value convertions are checked and updated and unwanted columns are deleted.

Conditional Columns are used to calculate the Attrition count and sort Age column.

3. Data Visualization: 
KPI Cards: Used to display overall employee count, Attrition and Attrition rate, Active Employees and Average Age.

### Attrition Rate is calculated using DAX formula
#### Attrition Rate = Sum('HR data'[Attrition count]')/Sum('HR data'[Employee count'])

PIE Chart: Used to Visualize the proportion or employees leaving by department, helping to identify which department have higher attrition.

Stacked Bar Chart: Represent attrition across different age bands and genders for each department, helping identify potential paetterns of attrition across segments.

Table( Job satisfaction Ratio): Provides insights into employee satisfaction for various roles across different satisfaction levels.

Bar Chart (Department-wise Attrition by Education Field): Breaks down attrition based on educational background, helping identify trends in attrition for employees from different educational fields.

Donut Charts (Attrition Rate by Gender for Different Age Groups): Displays the breakdown of male and female attrition across different age groups, providing insights into age- and gender-specific attrition trends.

![Image](https://github.com/user-attachments/assets/1df79c9b-bb45-4619-9e7f-884a43d7e996)


   
