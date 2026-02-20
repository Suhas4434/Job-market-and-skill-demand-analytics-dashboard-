# Job-market-and-skill-demand-analytics-dashboard-

Job Market & Skill Demand Analytics Dashboard Project Overview

This project analyzes job market trends using job portal data to identify:
Most demanded skills
Salary trends
City-wise job demand
Industry distribution
Experience-based salary growth
The dashboard was built using Power BI after data cleaning and transformation in Google Colab (Python).

📁 Dataset Information
Total Records: 4,473
Source: Job portal dataset (India, 2016)
Features Included:
Job Title
Industry
Skill Category
City
Experience (Years)
Average Salary
Posting Date

🧹 Data Cleaning & Transformation

Data preprocessing was performed in Google Colab using Python:
Removed missing and irrelevant columns
Extracted numeric salary from salary ranges
Converted experience into numeric format
Standardized city names
Extracted Year and Month from posting date
Handled missing values
Final cleaned dataset exported for Power BI.

📊 Dashboard Components
🔝 KPI Section
Total Jobs
Average Salary
Maximum Industry Salary
Salary per Experience


📈 Visualizations

Job Demand by Skill Category (Bar Chart)
Hiring Trend by Month (Line Chart)
Salary vs Experience (Scatter Plot)
Industry Distribution (Donut Chart)

🔍 Key Insights

IT Software sector dominates hiring demand.
Salary increases significantly with experience.
Metro cities (Bengaluru, Mumbai, Chennai) lead job postings.
Technical roles offer higher compensation.
Industry distribution shows technology-driven employment landscape.

🛠 Tools & Technologies Used
Python (Pandas, NumPy)
Google Colab
Power BI
DAX Measures


 Project Objective

To transform raw job market data into actionable insights using data cleaning, transformation, and interactive visualization techniques.

📌 Conclusion

This project demonstrates how structured data analysis can provide insights into:
Employment trends
Compensation patterns
Skill demand

Industry growth patterns

The dashboard enables decision-makers to explore hiring trends dynamically through interactive slicers and KPIs.
