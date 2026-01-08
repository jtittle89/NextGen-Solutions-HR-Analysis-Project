# NextGen-Solutions-HR-Analysis-Project
HR Power BI Analysis Project
📌 Project Overview

This project is an end-to-end HR analytics solution built in Power BI that analyzes employee demographics, engagement survey results, training performance, compensation, and attrition trends. The goal is to surface actionable insights that HR leaders and managers can use to improve retention, engagement, and workforce planning.

The report demonstrates advanced Power BI capabilities including data modeling, DAX measures, Power Query transformations, interactive dashboards, and automation using Power Automate.

📊 Dashboards Included
1. Employee Demographics

KPI cards for active employees, average employee age, and average employee tenure.

Active vs terminated employees.

Count of employees hired each year.

Employee ethnicity for each department.

Employee count by age group.

Interactive slicers for drill-down analysis.

<img width="1447" height="821" alt="image" src="https://github.com/user-attachments/assets/597d2c69-9a7d-4c67-87e8-76a87ef70880" />


2. Engagement Survey and Training Analysis

Analysis of employee survey scores (1–5 scale):

Engagement Score

Job Satisfaction

Benefits Satisfaction

Manager Rating

Correlation scatter plots with trend lines to identify relationships between key engagement drivers

Department-level comparisons and score distributions.

Analysis of employee score ratings by course and score group.

Training results compared to manager ratings.

Interactive slicers for drill-down analysis.

<img width="1432" height="816" alt="image" src="https://github.com/user-attachments/assets/a5ac6cfa-9214-4735-a0e8-3741c7882dab" />

4. Compensation Analysis

Salary distribution and compensation trends

Comparisons by department, role, and tenure

Identification of potential pay equity concerns

<img width="1436" height="815" alt="image" src="https://github.com/user-attachments/assets/cad4f2c7-efa5-4450-abcc-b2bf2708692c" />

5. Attrition & Turnover Analysis

Total terminated employees and termination rate

Average and median tenure of terminated employees

Attrition trends over time (by year)

Separation reasons analysis

Exit survey score analysis (min, avg, max) by department

Correlation between job satisfaction and exit survey scores.

Interactive slicers for drill-down analysis.

<img width="1443" height="818" alt="image" src="https://github.com/user-attachments/assets/d2c3c6a7-a898-4f4f-821e-80959cb6dc9c" />


🔧 Data & Modeling
Datasets Used
    
    Employees – demographics, hire dates, termination dates, tenure
    
    Engagement Survey – multi-year survey responses per employee
    
    Training – course completion and scores
    
    Compensation – salary and compensation data
    
    Exit Survey – exit feedback for terminated employees

Data Preparation

    Cleaned and transformed data using Power Query
    
    Handled nulls, standardized data types, and created derived columns (age groups, tenure, score bands)
    
    Built a relational data model with proper keys and relationships

📐 Key DAX Measures & Calculations

    Termination Rate (%)
    
    Average & Median Tenure (Terminated Employees)
    
    Engagement and Satisfaction Averages
    
    Min / Avg / Max Exit Survey Scores
    
    Attrition trends and cumulative metrics
    
    Correlation-ready measures for scatter plot analysis

🤖 Automation

    Integrated Power Automate to:
    
    Automatically export and email reports to stakeholders
    
    Demonstrate report distribution and operational analytics use cases

🎯 Key Insights

    Identified departments with higher attrition and lower exit satisfaction
    
    Highlighted strong correlations between manager ratings and engagement scores
    
    Revealed tenure patterns indicating early-employee attrition risks
    
    Showed training performance trends by department and course

🛠 Tools & Technologies

    Power BI (Data Modeling, DAX, Visualizations)
    
    Power Query (ETL & data cleaning)
    
    Power Automate (report automation)
    
    CSV datasets for structured data ingestion

🚀 How to Use

    Download or clone this repository
    
    Open the .pbix file in Power BI Desktop
    
    Refresh data connections (CSV-based)
    
    Explore dashboards using slicers and drill-downs

📈 Skills Demonstrated

    HR Analytics & Workforce Insights
    
    Data Modeling & Relationships
    
    Advanced DAX & KPI development
    
    Data Visualization & Storytelling
    
    Automation & Reporting Workflows

📌 Notes

This project uses synthetic HR data for demonstration purposes and does not represent real employee information.
