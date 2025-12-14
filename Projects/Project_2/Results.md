# Analyzing Salary Data by Visa Category in Tableau

This part focuses on analyzing salary data in relation to visa categories using Tableau, while demonstrating various steps to create and manipulate charts.

## Understanding Salary Data and Visa Categories
- We begin by hypothesizing that salaries may differ based on the type of visa (**Green Card vs. H1B Visa**) and suggests testing this hypothesis.
- It is emphasized that the cost implications of sponsoring green cards compared to visas, which may affect company sponsorship decisions.

## Creating Charts in Tableau
- Here it will be demonstrated on how to create a chart by placing **Paid Wage Per Year** on the **Rows shelf** and **Job Title Subgroup** on the **Columns shelf**, changing the aggregation to **Median** for better insights.
- A **duplicate worksheet** is created to allow for multiple visualizations simultaneously, enhancing the analysis process.

## Breaking Down Data by Visa Class
- The **Visa Class** variable is added to the **Columns shelf** to segment the data further, allowing for a comparison of salaries across different job titles and visa categories.
- In this analysis, Tableau demonstrated exceptional power and clarity in visualizing data — a stark contrast to the limitations of traditional methods like Excel.

## Exploring Data Details
- **View Data** options are introduced to access underlying data, providing insights into the number of records and specific values for each category.
- **Number of Records** were added to the **Rows shelf** to visualize the count of records contributing to each bar in the chart.

## Analyzing Variability with Standard Deviation
- **Standard deviation** was also calculated to assess the variability of salaries within each category, indicating potential outliers in the data.
- The difference between **population standard deviation** and **sample standard deviation** was also explored.

---
 <p align="center">
  <img src="Charts/Job_Title_Vs_Median_Paid_Wage_Per_Year.png" width="600" height="600"/>
</p>

## Result and Analysis

The above chart compares median annual wages across job titles segmented by visa class.  

- **Attorneys with E-3 Australian visas** earn the highest median salary, exceeding **$180,000 USD**.  
- **Teachers with H-1B1 Singapore visas** earn the lowest, below **$40,000 USD**.  
- Most technical roles (e.g., **data scientists**, **software engineers**) show moderate variation across visa types, but some visa categories consistently align with higher or lower pay.  
- The chart reveals how **visa class can significantly influence salary levels**, even within the same job title.  

This visualization highlights the intersection of immigration status and compensation, offering insights into labor market dynamics and sponsorship decisions.
