**ABC Company Employee Data Analysis**
************************************

Overview:
This project analyzes employee data from ABC Company (458 rows × 9 columns).  
The goal is to preprocess the dataset, perform meaningful analysis, and visualize key insights.

Preprocessing:
- Checked for missing values and handled them where necessary.
- Converted categorical variables into appropriate formats.
- Created **age groups** using binning.


**Analysis Tasks:**
1. **Team Distribution**
   - Counted employees per team.
   - Calculated percentage split relative to total employees.
   - Visualized using bar chart

2. **Position Segregation**
   - Grouped employees by job position.
   - Visualized using Seaborn bar plot.

3. **Age Group Analysis**
   - Created age bins (`<25`, `25–35`, `35–45`, `45+`).
   - Identified the predominant age group.
   - Visualized with bar chart.

4. **Salary Expenditure**
   - Calculated total salary by team and position.
   - Identified highest-cost team and role.
   - Visualized with horizontal bar charts.

5. **Age vs. Salary Correlation**
   - Computed Pearson correlation coefficient.
   - Visualized with scatterplot and regression line.

**Graphical Representations:**
- Bar charts (team & position distribution)
- Pie chart (percentage split by team)
- Age group distribution
- Salary expenditure comparisons
- Scatter plot of Age vs. Salary with trend line

**Key Insights:**
- Majority of employees are in the **25–35 age group**.
- The largest team is New Orleans Pelicans with 4.15 % of employees.
- Most employees are in the SG position with employee count 102.
- The highest salary expenditure is from team 'Los Angeles Lakers' and position 'SF', totaling 31,866,445.00.
- Correlation between Age and Salary: 0.21 (positive)

**Repository Contents:**
- `Employee Analysis Project.ipynb` → Notebook with code, plots, and explanations.
- `ABC Company.xlsx` → Dataset.
- `README.md` → Project overview and insights.
