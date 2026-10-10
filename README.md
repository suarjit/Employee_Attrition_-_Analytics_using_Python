# Employee_Attrition_-_Analytics_using_Python
Employee Attrition & Workforce Analytics Using Python
📌 Project Overview

Employee attrition is a major challenge for organizations because high employee turnover can increase recruitment costs, reduce productivity, and affect overall business performance.

This project uses Python, Pandas, NumPy, Matplotlib, and Seaborn to analyze employee data and identify patterns associated with employee attrition. It explores how factors such as department, overtime, monthly income, job satisfaction, age, work-life balance, and years of experience relate to employees leaving or staying with an organization.

The goal is to transform employee data into meaningful insights that can help HR teams understand workforce trends and develop better employee retention strategies.

🎯 Project Objectives
Calculate the overall employee attrition rate.
Identify departments and job roles with higher attrition rates.
Analyze the relationship between overtime and employee turnover.
Compare monthly income between employees who leave and those who stay.
Investigate the relationship between job satisfaction and attrition.
Examine how age and distance from home relate to employee turnover.
Understand the role of work-life balance in employee retention.
Compare workforce characteristics between employees who left and those who stayed.
Explore correlations between numerical variables and attrition.
Detect outliers in employee monthly income.
Generate actionable business insights to support HR decision-making.
🛠️ Technologies Used
Python – Data analysis and programming.
Pandas – Data manipulation, grouping, aggregation, and analysis.
NumPy – Numerical computations and statistical operations.
Matplotlib – Data visualization and chart creation.
Seaborn – Statistical visualization and exploratory data analysis.
Google Colab / Jupyter Notebook – Interactive development and execution.
📂 Project Structure
Employee-Attrition-Analytics/
│
├── Employee Attrition & Workforce Analytics using Python.ipynb
├── employee.csv
└── README.md


Note: Update the notebook filename and directory structure to match your repository.

📊 Dataset Description

The project uses an employee dataset named employee.csv.

The dataset includes employee attributes such as:

Attrition – Indicates whether an employee left the organization.
Department – Department in which the employee works.
JobRole – Employee's job role.
OverTime – Indicates whether the employee works overtime.
MonthlyIncome – Employee's monthly income.
JobSatisfaction – Employee's job satisfaction level.
WorkLifeBalance – Employee's work-life balance rating.
Age – Employee's age.
DistanceFromHome – Distance between home and workplace.
TotalWorkingYears – Total years of professional experience.
YearsAtCompany – Number of years spent at the organization.
YearsInCurrentRole – Number of years in the current role.
YearsSinceLastPromotion – Years since the last promotion.
YearsWithCurrManager – Years working with the current manager.

The analysis also examines other numerical and categorical columns available in the dataset.

🔍 Project Workflow
1. Data Loading and Exploration
Import the required Python libraries.
Load the employee dataset using Pandas.
Inspect the first few records, dataset dimensions, column names, and data types.
Check for missing values and duplicate records.
Separate numerical and categorical columns for further analysis.
2. Overall Attrition Analysis

Calculate the percentage of employees who left the organization and visualize the distribution of employees who stayed versus those who left.

Visualization: Employee attrition count plot.

3. Department-Wise Attrition

Calculate attrition rates across departments and rank departments based on their employee turnover rates.

Visualization: Attrition rate by department.

4. Overtime and Attrition

Compare attrition rates between employees who work overtime and those who do not.

Visualization: Overtime versus attrition count plot.

5. Monthly Income Analysis

Compare the average monthly income of employees who left with those who stayed to identify potential compensation-related patterns.

Visualization: Monthly income box plot grouped by attrition.

6. Job Satisfaction Analysis

Examine attrition rates across different job satisfaction levels to understand how satisfaction is associated with employee retention.

Visualizations:

Job satisfaction versus attrition count plot.
Attrition rate by job satisfaction level.
7. Distance From Home Analysis

Compare employees' average commuting distances and examine their distributions based on attrition status.

Visualization: Distance from home box plot.

8. Job Role Analysis

Identify job roles with higher employee attrition rates and compare turnover patterns across roles.

Visualization: Attrition rate by job role.

9. Age-Based Analysis

Compare the average ages of employees who left and stayed, and examine age distributions across both groups.

Visualizations:

Age box plot.
Age distribution histogram with KDE curves.
10. Work-Life Balance Analysis

Analyze attrition rates across different work-life balance ratings to explore possible relationships between work-life balance and employee retention.

Visualizations:

Work-life balance versus attrition count plot.
Attrition rate by work-life balance rating.
11. Employee Tenure and Workforce Comparison

Compare employees who left and stayed across several numerical variables, including:

Age
Monthly income
Distance from home
Job satisfaction
Work-life balance
Total working years
Years at the company
Years in the current role
Years since the last promotion
Years with the current manager

A box plot is also used to examine the relationship between company tenure and attrition.

12. Correlation Analysis

Convert the attrition column into a numerical representation:

No → 0
Yes → 1

Calculate correlations among numerical variables and visualize them using a correlation heatmap. Rank numerical variables by the absolute strength of their correlation with attrition to identify potential relationships for further investigation.

13. Outlier Analysis

Use the Interquartile Range (IQR) method to identify potential outliers in monthly income.

The analysis calculates the first quartile, third quartile, IQR, and lower and upper thresholds, then counts observations outside these thresholds.

Visualization: Monthly income box plot.

14. Department and Overtime Analysis

Use a cross-tabulation to compare attrition percentages across overtime categories within each department. This helps explore whether overtime-related attrition patterns vary between departments.

15. Business Insights

Summarize key findings, including:

Overall attrition rate.
Department with the highest attrition rate.
Attrition rates for employees who work overtime and those who do not.
Average income of employees who left and stayed.
Job role with the highest attrition rate.
Average ages of employees who left and stayed.
💡 Key Areas of Investigation

The analysis explores several workforce patterns:

Overtime: Whether employees working overtime have higher attrition rates.
Compensation: Whether average monthly income differs between employees who leave and stay.
Job satisfaction: Whether attrition rates vary by satisfaction level.
Age: Whether employees who leave differ in age from employees who stay.
Commute distance: Whether employees who leave tend to live farther from work.
Work-life balance: Whether retention patterns differ across work-life balance ratings.
Department and job role: Which workforce segments experience comparatively higher attrition.
Employee tenure: How years at the company and other experience measures differ by attrition status.

These are analytical questions rather than predetermined conclusions. Actual findings should be reported using the results obtained from the dataset.

📈 Business Value

The insights from this project can help HR teams:

Identify departments and job roles that may need further retention analysis.
Investigate workload and overtime practices.
Review compensation patterns across employee groups.
Explore employee satisfaction and work-life balance initiatives.
Examine onboarding, career development, and promotion opportunities.
Support data-driven workforce planning and retention strategies.

The findings indicate associations in the available data and should not be interpreted as proof that any single factor causes employee attrition.

⚙️ Installation and Setup
Prerequisites
Python 3.9 or later recommended.
Jupyter Notebook or Google Colab.
The employee.csv dataset.
1. Clone the Repository
git clone <your-repository-url>
cd Employee-Attrition-Analytics


Replace <your-repository-url> with your GitHub repository URL.

2. Install Dependencies
pip install numpy pandas matplotlib seaborn jupyter

3. Add the Dataset

Place employee.csv in the same directory as the notebook.

4. Run the Notebook

Launch Jupyter Notebook:

jupyter notebook


Open the project notebook and execute the cells in sequence.

Alternatively, upload the notebook and dataset to Google Colab and run the analysis there.

🧪 Methodology

The project uses the following analytical techniques:

Exploratory Data Analysis (EDA)
Data quality checks
Grouping and aggregation
Attrition rate calculations
Comparative statistical analysis
Data visualization
Correlation analysis
Interquartile Range (IQR) outlier detection

The analysis primarily uses descriptive statistics and visualization to identify patterns in employee attrition.

🚀 Future Improvements

Potential extensions include:

Develop an interactive HR analytics dashboard using Power BI, Tableau, or Plotly.
Build machine learning models to predict employee attrition.
Evaluate model performance using precision, recall, F1-score, and ROC-AUC.
Identify important predictors using feature importance or explainability techniques.
Add department-level and job-role-level filters to an interactive dashboard.
Develop employee retention recommendations based on validated findings.
Perform statistical significance testing to evaluate observed differences.
Improve data validation and handling of missing or inconsistent values.
⚠️ Limitations
The analysis depends on the quality and completeness of the supplied dataset.
Correlation does not establish causation.
Average values can hide differences within employee groups.
Observed attrition patterns may not generalize to other organizations.
The current project focuses on descriptive analytics rather than predictive modeling.
Any recommendations should be validated with additional organizational context before implementation.
👤 Author

Your Name

GitHub: Your GitHub Profile
LinkedIn: Your LinkedIn Profile

Replace the placeholder links with your actual profile URLs.

📄 License

This project is intended for educational and analytical purposes. Add a license, such as the MIT License, if you want to distribute the project under specific open-source terms.

If you find this project useful, consider giving the repository a ⭐ on GitHub!