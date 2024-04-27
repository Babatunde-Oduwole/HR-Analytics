# HR-Analytics

![HR-Analytics-768x512](https://github.com/Babatunde-Oduwole/HR-Analytics/assets/167521089/25db105e-26b8-4314-bf34-3f3302cc2ac1)


## Table of Contents

- [Project Introduction](#Project-Introduction)
- [Data Source](#Data-Source)
- [Tools](#Tools)
- [Data Cleaning/Preparation](#Data-Cleaning/Preparation)
- [Exploratory Data Analysis (EDA)](#Exploratory-Data-Analysis)
- [Findings](#Findings)
- [Recommendations](#Recommendation)
- [Limitations](#Limitations)

### Project Introduction


The primary focus of this project is to understand employee demographics, performance metrics, and attrition patterns to identify trends and inform HR policies. The dataset comprises employee details, including age, gender, department, job role, salary, tenure, and attrition status. The goal is to generate actionable insights to improve workforce diversity, and enhance employee engagement.

### Data Source

The primary dataset used for this analysis is the 'HR_data.xlsx' file, containing detailed information about employment details of all staff in the company.

### Tools

1. MySQL - Data Analysis
2. Power BI - Data cleaning and Visualization

### Data Cleaning/Preparation

In the initial data preparation phase, the following tasks were performed:
1. Checked for missing values, inconsistencies, and outliers across all data fields.
2. Ensured consistency in data formats and structures by standardizing date formats and ensuring uniformity in categorical variables like department names and job roles.
3. Identified and removed duplicate entries to prevent skewed analysis.
4. Transformed data into appropriate formats for analysis.
   
### Exploratory Data Analysis (EDA)

EDA involved exploring the HR data to answer key questions, such as:

1. What was the total numbers of employee?
2. What was the attrition count?
3. What was the the attrition rate?
4. What was the average age of all employees?
5. What was the total numbers of active employees?
6. What was the atrrition by department?
7. What was the atrrition by education field?
8. What was the job satisfaction rating?
9. What was the attrition by gender across age groups?


### Findings
Below are some of the finding discovered after analysis:
1. The company's workforce is quite young because the largest portion of their employees are within youthful age, i.e between the age of 25-44 years old.
2. The attrition rate of male employees across all age group is high, and this need to be looked into, this could have a negative impact on the organization in ashort period of time.
3. There is a relatively low attrition rate in the HR department while the R&D, and Sales department has a high level of attrition rate.


### Recommendations

Based on the analysis, the following recommendations are suggested for actions:

1. Young employees are often ambitious and eager to progress in their careers. Implementing clear career paths, mentorship programs, and continuous learning opportunities will reduce attrition.
2. Creating a vibrant and inclusive workplace culture can help retain younger employees. The company should organize team-building activities, social events, and employee recognition programs to foster a sense of belonging and ownership.
3. The company should determine the reasons behind male attrition through structured exit interviews and employee surveys. This can provide insights into the root causes and guide further actions.
4. After determining the reason for the high rate of male attrition, if the company discover it is due to financial reasons, they should ensure that compensation packages and benefits are competitive and aligned with industry standards.
5.  The company should create channels for employees to provide feedback on workplace issues, allowing the organization to address concerns promptly.Leaders should also be encouraged to be actively involved in employee engagement and retention efforts to create a positive organizational culture.
   
### Limitations

During data cleaning, all null values from all columns were cleaned because they will affect the accuracy of the analysis. There are still a few outliers even after the omissions but even then, there are positive correlation between the data and the result of the analysis. 

