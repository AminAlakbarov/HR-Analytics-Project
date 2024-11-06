# HR Analytics Dashboard - Power BI Project

This repository contains a Power BI project focused on analyzing HR data, offering insights into workforce demographics, salary distribution, tenure trends, and hiring patterns. The dashboard provides an interactive overview for HR teams and business leaders, enabling data-driven decisions in workforce planning, compensation strategies, and policy development.

---

## Data Fields

The dataset includes various fields relevant to employee demographics and HR metrics:
- **Employee Name**: Full name of the employee.
- **Department**: The department where the employee works.
- **Position**: Job title or position of the employee.
- **Gender**: Gender identity of the employee.
- **Age**: Employee’s age.
- **Tenure**: Number of years the employee has been with the organization.
- **Salary**: Salary of the employee.
- **Hire Date**: Date the employee joined the organization.

---

## Measures and Calculations

The *Measure Table* includes several DAX measures designed to highlight key HR metrics and trends within the organization. Below are the measures available in this report:

- **Average Age**: The average age of all employees.
- **Average Salary**: The average salary across all employees.
- **Average Tenure**: The average number of years employees have been with the organization.
- **Female Employees**: The count of female employees in the organization.
- **Male Employees**: The count of male employees in the organization.
- **Total Employees**: The total number of employees.
- **Total Salary**: The sum of all employee salaries.

---

## Dashboard Visualizations

### 1. Demographic Analysis Page
- **Total Salary by Age Group**: A bar chart visualizing salary distribution by age group, split by gender.
- **Total Salary by Tenure Range**: A bar chart showing salary distribution by tenure groups for each gender.
- **Average Salary, Tenure, and Age KPIs**: Display average salary, tenure years, and age for the workforce.
- **Gender Distribution**: A donut chart representing the workforce's gender composition.

### 2. Compensation Analysis Page
- **Hiring Trends**: Line chart indicating the number of hires over time.
- **Salary by Position**: Bar chart displaying the salary distribution by different positions.
- **Salary by Department**: Bar chart showing total salary distribution across departments.
- **Employee Details Table**: A detailed table of individual employee information, including tenure, age, and salary, with conditional formatting for added insights.

---

## Filters

The dashboard offers interactive filtering options to enhance analysis:
- **Department**: View data by specific departments.
- **Position**: Focus on specific positions or job titles.
- **Gender**: Filter results by gender.
- **Age Group**: Narrow down the view based on specific age ranges.
- **Tenure Range**: Analyze data based on employee tenure groups.
- **Year**: Filter data by hire date for year-specific insights.

---

## Project Goals

The primary objectives of this dashboard are:
- To provide HR teams with insights into workforce demographics and trends.
- To assist in identifying patterns in compensation by department and position.
- To support strategic decision-making in hiring, retention, and workforce planning.
- To offer an interactive, data-driven overview of employee data with customizable filters.

---

## Contributing

Contributions to this project are welcome, whether adding new DAX measures, improving existing visualizations, or optimizing dashboard performance

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.