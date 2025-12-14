# Identifying Outliers with Scatter Plots in Tableau

### 1. Creating Scatter Plots
- Scatter plots help identify unusual data points (outliers) visually.
- Start by duplicating an existing chart (e.g., *Median Wage Per Subgroup*).
- Work on the duplicate so the original chart remains unchanged.

### 2. Analyzing Standard Deviations
- Standard deviation shows how spread out the data is.
- Subgroups with very high deviations may contain outliers.
- In this example, the *Attorney* subgroup has unusually large variation.
- Change chart marks from bars to shapes for clearer visualization.

### 3. Building the Scatter Chart
- Go to **Analysis → Aggregate Measures** and uncheck it.
- This displays each individual data point instead of aggregated values.
- Adjust the size and shape of marks (e.g., circles) for clarity.

### 4. Using Filters
- Filters allow to hide extreme values.
- Drag *Paid Wage Per Year* onto the **Filters shelf**.
- Set a maximum threshold (e.g., 1.5 million) to exclude unrealistic values.
- Use **Quick Filter** to adjust the range interactively (Show Filter).

### 5. Grouping Outliers
- Select specific outlier points, right‑click, and choose **Group**.
- Tableau creates a new variable (e.g., *Case Number Group*) separating outliers from the rest.
- This lets one compare “Outliers” vs “Other” in future analyses.

### 6. Exploring Data Without Outliers
- Once grouped or filtered, analyze the dataset without extreme values.
- Compare education levels, regions, or experience years between outliers and others.
- This helps determine whether outliers are errors, special cases, or meaningful insights.

---
