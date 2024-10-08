# HR Performance Metrics and Retention Analysis Report

## 1. Introduction
This project focused on analyzing and predicting employee retention to assist the organization in enhancing its HR strategies and reducing turnover.
## 2. Workforce Demographics

### 2.1 Gender Distribution
<br>

![image](https://github.com/user-attachments/assets/dc317cf4-f4b0-424d-bd08-193193ea3f87)

<br>

![image](https://github.com/user-attachments/assets/a3c0155b-14fc-4bfc-90e9-8205aacc4839)
<br>

**Key Finding:** 
The company's workforce is predominantly female, with women making up 56.5% of the total employees. However, in departments like IT and Sales, there are more male employees than female ones. This shows that, although females make up the majority company-wide, men are more prevalent in these specific departments.

<br>
<br>

### 2.2 Age Distribution
<br>


![image](https://github.com/user-attachments/assets/39d4eaac-8f2a-4ab4-a5f1-80632a9ea5ed)


**Key Finding:** 
The age distribution at hiring shows a broad range with some notable patterns. The majority of hires fall between 24 and 29 years old. A significant number of hires occur in the age range of 27 to 29 years, with 33 hires recorded.

The age at hiring ranges from a minimum of 19 years to a maximum of 63 years. Notably, the median age is 32 years, and 75% of hires are 39 years old or younger, indicating that most employees are hired within a relatively young age range.



## 3. Salary Analysis

### 3.1 Overall Salary Distribution
<br>

![image](https://github.com/user-attachments/assets/963495cd-35bc-4cce-aa99-3606a8b877bf)


**Key Finding:** 
The salary distribution in the dataset shows considerable variation, with a right-skewed distribution. This skew implies that a portion of employees earn significantly higher salaries, pulling the mean (69,020.68) upwards compared to the median(62,810.00). Specifically, the presence of a maximum salary as high as $250,000.00 indicates outliers or high earners in the dataset. This distribution should be considered when evaluating salary equity and making compensation decisions.

<br>

### 3.2 Salary by Department

<br>

![image](https://github.com/user-attachments/assets/21883e2b-0a11-4188-b85f-d3b2fc8f9c22)


**Key Findings:** 
Production salaries are relatively close to the median (59,472.00) with a broad range at the upper end. The average (59,953.55) is slightly higher than the median, suggesting that higher salaries are pulling up the average. The maximum salary (170,500) is considerably higher than the 75th percentile (64,066.00), indicating possible outliers or specialized roles with high compensation.

The IT/IS department exhibits a high average salary (97,064.64) with significant variability. The maximum salary (220,450.00) is notably higher than the 75th percentile (106,844.50), suggesting the presence of high earners or potential outliers . The wide range between the 25th (77,417.75) and 75th percentiles indicates a diverse salary structure.

Software Engineering shows high average (94,989.45) and median (95,660.00) salaries with a relatively narrow range between the 25th (89,601.50) and 75th (100,807.50) percentiles, suggesting consistent compensation levels. The maximum salary (108,987.00) is higher than the 75th percentile, indicating the presence of high earners.

The Admin Offices show a considerable salary range with a maximum salary ($106,367.00) that is significantly higher than the median (63,003.00). The average salary (71,791.89) is higher than the median, suggesting a few high earners could be skewing the average. The gap between the 25th (55,000.00) and 75th (93,046.00) percentiles indicates variability within this department.

Sales department salaries are fairly balanced with the average (69,061.26) close to the median (65,310.00). The maximum salary (180,000.00) is significantly higher than the 75th percentile (70,506.50), suggesting a few high earners. The relatively narrow range between the 25th (61,561.50) and 75th percentiles indicates moderate variability.

The Executive Office currently has a single employee in the dataset, therefore the salary data reflects only one individual’s compensation (250000.00). As a result, there is no variation or outliers in the pay structure for this department.

<br>
<br>

### 3.3 Salary by Gender and Age
<br> 

![image](https://github.com/user-attachments/assets/17f13ef3-ff5f-4dfb-ba66-46297f208af5)

**Key Findings:** 
The scatterplot analysis reveals that earnings do not vary significantly by gender across the dataset. However, it is notable that the highest earners are predominantly female. Additionally, there is a marked decrease in high earners among employees older than 63, indicating that high earnings are concentrated within younger age groups.


## 4. Employee Tenure and Performance

### 4.1 Tenure Distribution
<brr>
  
![image](https://github.com/user-attachments/assets/af86bd71-b6be-4370-be74-14a0316ed2a0)


**Key Finding:** 
The tenure range from 9.50 to 10.45 years has the highest number of employees, with 56 employees, indicating that this is a common tenure range among employees.There may be a need to focus on retention strategies and career development for employees around this tenure, as they represent a significant portion of the workforce.

Ranges with very low employee counts include 14.25 to 15.20 years (1 employee), and 17.10 to 18.05 years and 18.05 to 19.00 years (0 and 1 employee respectively). These ranges have fewer employees, indicating they are less common. The low count of employees in the higher tenure ranges indicates potential opportunities for developing strategies to retain long-term employees and provide career growth opportunities to extend tenure.

<br>

### 4.2 Performance Scores
<br>

![image](https://github.com/user-attachments/assets/601d0ad1-1151-440d-bdd5-2e32596c7bf9)


**Key Findings:**
The performance score distribution within the organization reveals that 78.1% of employees are classified as Fully Meets, indicating that a significant majority are meeting their performance expectations. 11.9% of employees are in the Exceeds category, representing high achievers who perform above expectations. Meanwhile, 5.8% of employees fall under Needs Improvement, suggesting areas where additional support may be required. Lastly, 4.2% of employees are currently under a Performance Improvement Plan (PIP), reflecting a small group facing more serious performance challenges.


### 4.3 Performance vs Tenure

<br>

![image](https://github.com/user-attachments/assets/7e3d2e1a-f5e4-4689-a19e-3d4546a7e12f)


**Key Finding:** 
Employees with a performance score of "Exceeds" have the longest average tenure at 9.86 years, with a median tenure of 10 years. They also exhibit a high range in tenure, from 2 to 19 years, reflecting a broad distribution among top performers.

In the "Fully Meets" category, employees have an average tenure of 8.37 years and a median tenure of 10 years. This group shows a tenure range from 0 to 17 years, indicating a mix of newer and more established employees who meet performance expectations.

Those categorized as "Needs Improvement" have a lower average tenure of 7.39 years and a median tenure of 6.5 years. Their tenure ranges from 2 to 14 years, suggesting shorter tenure compared to higher performance categories.

Employees on a "PIP" have an average tenure of 7.92 years and a median tenure of 9 years. The tenure for this group ranges from 1 to 13 years, reflecting relatively shorter tenures and indicating potential issues with long-term retention among those in performance improvement plans.


## 5. Retention Risk Analysis

### 5.1 Turnover Rate by Department
<br>

![image](https://github.com/user-attachments/assets/11e3893f-1dc9-4d67-ba7b-94eb60820aa8)


**Key Finding:** 
Turnover rates vary significantly across departments
Some departments show notably higher turnover rates, indicating areas of concern
Departments with lower turnover rates may offer insights into effective retention strategies


## 6. Department-Specific Insights

<br>
  
![image](https://github.com/user-attachments/assets/ab41cd2f-1efd-4e23-9f7f-64f8a384993d)

<br>

![image](https://github.com/user-attachments/assets/79a06c42-c4b0-41b7-80ac-85db1c53dfd5)

**Key Findings:**
Production employees have an average tenure of 8 years and a median of 10 years, with a maximum tenure of 17 years, reflecting a broad range of experience within the large group of 209 employees.

In the IT/IS department, employees have an average tenure of 8.24 years, with a median of 9 years and a maximum tenure of 14 years, indicating a stable range of experience among the 50 employees.

Software Engineering employees have an average tenure of 8.64 years, with a median of 10 years and a maximum of 13 years, showing a good level of experience within the 11 employees.

The Admin Offices department has an average tenure of 9 years, with a median tenure of 10 years and a maximum of 16 years. However, due to a small sample size of 9 employees, there is a relatively high variability in tenure.

The Sales department has the highest average tenure at 10.06 years, with a median of 10 years and a maximum of 19 years, suggesting a strong retention rate among 31 employees.

Lastly, Executive Office shows a single employee with a tenure of 12 years, resulting in no standard deviation due to the lack of variance.


## 7. Recommendations

1. Prioritize regular performance reviews and feedback
2. Develop a structured career progression framework
3. Implement targeted retention programs for high performers
4. Address engagement and satisfaction through tailored initiatives
5. Review and adjust compensation strategies to align with performance
6. Focus on diversity and inclusion across all departments
7. Create mentorship programs to transfer knowledge from long-tenured employees

## 8. Next Steps

1. Conduct deeper analysis on engagement and satisfaction factors
2. Implement predictive model to identify at-risk employees
3. Develop action plans for each department based on their unique characteristics
4. Establish a system for regular workforce analytics updates
