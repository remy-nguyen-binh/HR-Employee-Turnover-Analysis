# HR Employees Turnover Analysis
## Project Overview
The objective of this analysis is to identify the common factors that contribute to a high turnover risk among employees. High employee turnover can lead to increased costs, reduced productivity, and a loss of organizational knowledge, making it crucial for HR departments to understand the drivers behind this issue.

## Dataset Overview
The dataset for this analysis consists of 1,000 employee records from an HR Information System (HRIS). Each record includes variables such as Employee ID, Department, Position, Salary, Performance Score, Job Satisfaction Score, Sick Days Taken, Training Hours, Overtime Hours, and Turnover Risk. The dataset provides valuable insights into employee demographics, work performance, and compensation, enabling a detailed exploration of factors affecting turnover.

You can download the raw excel file [here](https://github.com/remy-nguyen-binh/HR-Performance-Salary-Analysis/blob/main/HRIS_HR_Analyst_Dataset.csv)

## Stakeholder Question
What are the common factors (e.g., salary, sick days, job satisfaction) among employees with a high turnover risk?

Understanding these factors can help the HR team implement strategies to retain employees by addressing key concerns, thereby improving overall organizational stability.

## Tool
I am using Power BI for data cleaning, data analysis and visualization for this project.

## Data Analysis steps
### Data cleaning
- Remove any duplicate or missing records.
- Standardize data formats for dates, salaries, and other numerical fields.

### Exploratory Data Analysis (EDA):
- Perform summary statistics for key variables like salary, job satisfaction, sick days, and turnover risk.
- Visualize the distribution of employees across different departments, job roles, and work locations.

### Correlation Analysis:
- Calculate correlations between turnover risk and other key factors such as salary, job satisfaction, and sick days taken.
- Identify any significant relationships between these variables.

### Segmentation Analysis:
- Segment employees into different turnover risk groups (Low, Medium, High) and compare their average salary, job satisfaction scores, and other factors.
- Use pivot tables and charts to examine patterns across departments and positions.

## Key Insight
- The turnover rate is high among employees with high salaries in general in Finance, HR, and Sales. 
- The turnover rate is highest among employees in Sales and lowest in HR.
- The average salary with high turnover rate is $80.770.
- Among 1000 staffs of the company, there are 340 employess having high risk turnover that has 158 employees with high salary. 
- The low performance score is very high in IT and the high performance score is high in Finance.

## Hypothesis

1. **Job Satisfaction and Engagement**: High-salary employees in Finance, HR, and Sales may experience dissatisfaction or lack of engagement, leading to higher turnover rates.
   
2. **Workload and Job Stress in Sales**: Sales employees may face high-pressure targets and stressful work environments, contributing to the highest turnover rates in that department.

3. **Career Advancement Opportunities**: Employees in Sales and Finance may perceive limited career growth or development opportunities, prompting them to seek better roles elsewhere.

4. **Work-Life Balance**: High-salary employees in Sales and Finance may struggle with poor work-life balance, leading to higher turnover compared to HR, where work conditions may be more stable and balanced.

5. **Compensation and Performance Link**: The $80,770 average salary for those at high risk of turnover could indicate that compensation alone is not enough to retain employees, especially when job satisfaction, recognition, or performance incentives are lacking.

6. **Departmental Culture and Fit**: The low performance scores in IT and high scores in Finance may point to cultural or management issues in IT that impact employee morale and performance, potentially contributing to higher turnover risks.

7. **Skill Mismatch in Sales and IT**: The high turnover in Sales and low performance in IT may be due to a mismatch between employee skills and job requirements, leading to job dissatisfaction and attrition.

8. **Talent Poaching and Market Competition**: High-performing Finance employees may be targeted by competitors or more attractive offers, driving higher turnover rates despite strong performance scores.

9. **Management and Leadership Influence**: Differences in turnover between departments like Sales and HR may be driven by variations in management practices, with stronger leadership and employee support in HR reducing turnover.

## Recommendations

1. **Enhance Employee Engagement**: Implement regular surveys and feedback mechanisms to gauge job satisfaction and engagement among high-salary employees, particularly in Finance and Sales.

2. **Review Compensation Structures**: Assess the compensation and benefits packages to ensure they are competitive and aligned with industry standards, particularly for high-risk turnover roles.

3. **Support Career Development**: Create clear career pathways and development programs for employees in Sales and Finance to foster growth and retention.

4. **Promote Work-Life Balance**: Encourage flexible work arrangements and wellness programs to improve work-life balance, especially in high-pressure departments like Sales.

5. **Implement Recognition Programs**: Establish recognition and reward programs for high-performing employees, particularly in Finance and HR, to reinforce positive performance and job satisfaction.

6. **Address Performance Issues in IT**: Investigate the underlying causes of low performance scores in IT and implement targeted training, support, or management changes to improve morale and productivity.

7. **Foster a Positive Culture**: Focus on building a positive organizational culture that emphasizes collaboration, support, and respect across all departments, particularly in those with higher turnover.

8. **Develop Exit and Stay Interviews**: Conduct exit interviews to understand the reasons for turnover and stay interviews to identify factors that encourage retention, particularly among high-risk employees.

9. **Strengthen Management Practices**: Provide training for managers to enhance their leadership skills, focusing on supporting team members and fostering a positive work environment.

10. **Monitor Turnover Metrics**: Continuously track and analyze turnover metrics across departments to identify trends and implement timely interventions where necessary.
