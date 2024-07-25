### HR-Data-Analytics_Python-Project
Identify the patterns that could impact satisfaction and productivity of the employees.

### Project Overview
- The primary goal here is to work towards the betterment of employees and to make an employee friendly environment. Recently the organisation has started collecting data from employees about their satisfaction towards the company along with internal review of the employee performance.
- They are interested in the factor/s that affect the satisfaction of employees along with their increased productivity.

### Problem Statement
- The organisation aims to optimise the environment and productivity of employees. To accomplish this goal, we need to understand extremes, patterns and associations with applications of probability and distributions.

### Formalization of problem
-Break down the main goals for the organisation entity using the questions provided.
  - Understand the distributions and patterns within the HR data.
  - Analyse the extremes within the data.
  - Answering key questions related to probability and distributions of the data.

### Data Handling and Processing
- Data contains a couple of samples randomly selected from mass employees working for MNCs.
- Data download and imported to Jupytor Notebook "HR Data Analytics.csv" file.
- Data inspection and cleaning
- Treating missing values and standardised the format
- Check the outliers

### Data Analysis
Part 1) Understanding the distributions and patterns within the HR data.
- We want to understand why an employee has a satisfactory or unsatisfactory performance as compared to excellent/outstanding performance.
  a) Mode of the employee performance in the rating column - Excellent
  b) Range of hours the employee is working for in case of unsatisfactory rating - Min: 0.091720, Max: 8.489765
By calculating the stat, we are able to understand the performances of Ratings
Lower ratings are given to employees who are working for lesser hours.
After analysing the histogram and box plot, we can see that the majority of the Hours are centred around 8 to 14 which clearly indicates the outliers towards the higher and lower side.
Also, the majority of employees are giving 6 or 7 satisfaction scores which means that the majority of employees aren’t that happy due to lower work life balance. 

Part 2) Identifying and excluding the outliers!
- Identifying the cut off values in order to deal with outliers.
- The congestion rates are part of a realistic scenario and not because of some error in the data. Therefore, it's better to continue with the analysis as such.
  
Part 3) Understanding probability distributions and Confidence interval
- We can see, higher number of hours have higher chances of occurrence rather than lower ones.
- The probability that 2 out of a sample of 10 employees are rated as outstanding is 0.18
- The probability that at least 3 out of a sample of 10 employees are rated as outstanding is 0.06
- The probability that at least 7 out of a sample of 10 employees are rated as outstanding or Excellent is 0.15
- The probability that None of the trainees are rated as Unsatisfactory is 0.37

### Findings
- The organisation somehow rewards the employees working for a high number of hours within the organisation. This could actually be counterproductive as the employees tend to slow and sluggish after a certain point. 
- We observed the highest frequency is for Excellent rating where employees tend to provide a good amount of working hours in general.

### Recommendations
- Estimating the hours of service that will be needed in a project beforehand for proper allocation of manpower.
- Higher working hours should be reserved for extreme deadlines or until and unless absolutely necessary.
- The management should focus on better work life balance which means these scales should be estimated based on individual performances and their impact on the project rather than on the number of hours of service provided. 
