# Analyzing Salary Data in Different States Using Filtering and Groups

## Objectives of the Presentation

- To analyze how salaries vary across different states in the U.S withing Job Subgroups.  
- To demonstrate the use of Tableau for visualizing salary data effectively.  
- To provide insights into which states offer higher salaries for specific job roles in the data analysis field.  

---

# Steps Taken to Create the Chart

## 1. Identify Relevant States
- Focused on states with significant tech industries:  
  *California, Washington, North Carolina, Colorado, Texas, New York, Massachusetts, Alabama*  
- Included *Maine* as a control state with a smaller tech presence.

## 2. Create a New Worksheet in Tableau
- Initiated a new worksheet to begin the analysis.

## 3. Add Filter for Work State
- Dragged the **Work State** variable into the filter section.  
- Used the filter GUI to select specific states for analysis.

## 4. Address Data Inconsistencies
- Dataset contained both full state names and abbreviations.  
- Applied Tableau’s **Grouping** feature to unify state names.

    ### Group States
    - Selected multiple entries and grouped them under a single state name.  
    - Ensured consistency across the dataset.

    ### Include 'Other States' Category
    - Added an **Other States** category to capture ungrouped states.  
    - Simplified filtering for future analysis.

## 5. Visualize Salary Data
- Placed **Paid Wage Per Year** in the Rows shelf (Median).  
- Placed **Job Title Subgroup** in the Columns shelf (Dimension).  
- Added grouped **Work State** variable for breakdowns.

## 6. Apply Color Coding
- Dragged **Work State** to the Color shelf.  
- Differentiated **Work State** visually for clarity.

## 7. Analyze Salary Trends
- Examined chart trends:  
  - Data scientist salaries varied significantly by state.  
  - Data analyst salaries remained more consistent.

## 8. Reorder Job Categories
- Adjusted the order of job categories based on salary values.  
- Improved clarity and insight.

## 9. Add Additional States
- Edited groups to include new states (e.g., *New Hampshire*).  
- Expanded analysis scope as needed.

---

<p align="center">
  <img src="Charts/Analyzing_Salary_Data_by_Visa_Category.png" width="80%" height="80%">
</p>

## Result and Analysis

The above chart compares median annual wages across U.S. states for various job titles from 2008 to 2015.

- **Attorneys in California** earn the highest median salary, exceeding **$160,000 USD**.  
- **Teachers in Maine** have the lowest median salary, below **$50,000 USD**.  
- Technical roles like **data scientists** and **software engineers** show strong salaries in states like **California**, **Massachusetts**, and **Washington**.  
- States such as **Alabama**, **Maine**, and **North Carolina** tend to offer lower compensation across most job categories.  

This visualization highlights significant **regional disparities in salary levels**, offering insights into how geography influences compensation across professions.

  ## INDEX

  ### Screenshot From The Project's Tableau Dashboard
<p align="center">
  <img src="Charts/Analyzing_Salary_Data_by_Visa_Category4.png" width="110%" height="110%">
</p>
