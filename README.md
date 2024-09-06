# Human Resources Exploratory Data Analysis using Python

## Project Recap
* **Tools:** Python
* **Libraries Used:** Pandas, Matplotlib, Seaborn
* **Skills Gained:** Data Cleaning/Processing, Data Visualization
* **Dataset:** https://www.kaggle.com/datasets/whenamancodes/hr-employee-attrition

<br>

## Background
A Co Ltd. is a technology company who has over 1000 employees. Recently, the company has been having a problem regarding employee attrition, and the company needs Data Team to provide insights regarding the cause of attrition. 

<br>

The management team wants Data Team to provide insight on these areas:
* Job Characteristics, such as payment. Employees tend to leave their jobs to take higher paying jobs somewhere else.
* Job Environment: Conflict, participation in decision making, and environmental fit. Relationship with supervisor has a big role in turnover decision, and employees who have many connections to the organization are less likely to leave.
* Job Dissatisfaction: It is one of the most consistent cause of turnover, and employees who are compatible with his job are more likely to stay.

<br>

## Data Understanding
The company's employee data contains roungly 1400 rows with 35 different columns, with details as follows:
* **Age**
* **Attrition**: Wheter the employee has left the company/not.
* **BusinessTravel**: Business Travel Frequency.
* **DailyRate**
* **Department**
* **DistanceFromHome**
* **Education**: Level of education. Higher number indicates higher education, starting with below college (1) and doctor (5).
* **EducationField**: Major of Education.
* **EmployeeCount**
* **EmployeeNumber**
* **EnvironmentSatisfaction**: Survey result. Higher number indicates higher satisfaction.
* **Gender**
* **HourlyRate**
* **JobInvolvement**: Survey result. Higher number indicates higher involement.
* **JobLevel**: Higher number indicates highler level in the company.
* **JobRole**
* **JobSatisfaction**: Survey result. Higher number indicates higher satisfaction.
* **MaritalStatus**
* **MonthlyIncome**
* **MonthlyRate**
* **NumCompaniesWorked**: Number of companies worked before at current company.
* **Over18**
* **OverTime**
* **PercentSalaryHike**
* **PerformanceRating**: Higher number indicates higher performance.
* **RelationshipSatisfaction**: Survey result. Higher number indicates higher satisfaction.
* **StandardHours**
* **StockOptionLevel**
* **TotalWorkingYears**: Year of experience in career.
* **TrainingTimesLastYear**
* **WorkLifeBalance**: Survey result. Higher number indicates higher work life balance.
* **YearsAtCompany**: Number of years in the company.
* **YearsInCurrentRole**: Year of experience in the same job role.
* **YearsSinceLastPromotion**
* **YearsWithCurrManager**: Number of years worked with the current manager.

<br>

## Data Processing

**Data Exploration:** <br> 
Exploring the data to gain insight and clean the data by changing data types, removing duplicated values, handling missing values and removing outliers if needed. 
* **Data Types**: All data types for 35 columns are in accordance with values inside the column.
* **Missing/Null Values**: There were no missing values in all of the columns.
* **Drop Column**: Columns 'EmployeeCount', 'Over18', and 'StandardHours' were each removed because each of them contained only 1 value. We cannot gain insight if all the values are the same. For that reason, the three columns were dropped.
* **Outliers**: There are no particular outliers that needs to be removed.

<br>

**Data Visualization**: <br>
Python libraries such as Matplotlib and Seaborn were used to create informative and visually appealing charts and graphs that illustrates attrition patterns. The visualizations include a variety of formats, such as combined histogram and line chart, correlation matrix, and bar chart. These graphical representations helps the Data Team to analyze the relationships between various factors within the dataset to generate valuable insights.

<br>

[Click here](https://github.com/rafifrzd/HR-Data-EDA-Python/blob/main/code/Project_2_Python%20-%20Final.ipynb) to see all Data Processing, Visualization, and coding process. 

<br>

## Insights
* **Low-Paid Employees Are Leaving**: Employees are more likely to quit if they earn around $2,000-5,000. They are typically in lower job levels with less than five years of experience.
* **Unhappy with Relationships and Environment**: Even though fewer employees fall into this group, employees with very low satisfaction in relationships and their work environment are leaving at higher rates (attrition rate over 20%) compared to those with better satisfaction (attrition rate 13-15%).
* **Less Involved Employees Are Leaving**: Employees who feel less involved in their jobs have a higher turnover rate (21.5%) than those who feel more involved (15.7%).
* **Dissatisfied Employees Are Quitting**: Employees with very low job satisfaction are more likely to leave (attrition rate over 20%), compared to those who are more satisfied (attrition rate around 10%).




















