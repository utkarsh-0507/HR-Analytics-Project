# HR-Analytics-Project

<img width="865" height="487" alt="image" src="https://github.com/user-attachments/assets/5dd4315b-1c92-4aaa-8c14-8aab6db47cf5" />

#Data Cleaning
1. Removed Colums which have empty or null values.

2. Removed duplicates, replaced the value of TravelRarely to Travel_Rarely.

3. Added Conditional Column named AttritionCount ; If Attrition values 'Yes', then output = 1 else 0.

#Data Insights
* Added a new measure;
  AttritionRate = SUM(HR_Analytics[Attrition Count]) / SUM(HR_Analytics[EmployeeCount])
  Similarly based on the formula as Total Attrition/Total Employees.

* Made few KPI's as Count of Employees = 1470; ∑ AttritionCount = 237; AttritionRate = 16.1%; Avg Age = 37; Avg Salary = 6.5K &
  Avg Yrs of Experience = 7.0.

* Made few charts such as Donut Chart, Stacked Column Chart, Matrix, Stacked Bar Chart, Area Chart, Treemap etc to show the overall
  data insights based on the report.

#Project Learnings

1. Identified key factors to reduce Attrition.

2. Improved hiring process.

3. Improved Employee experience.

4. Made workforce more productive.

5. Gained employee trust.

  
