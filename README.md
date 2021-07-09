# School District Analysis

## Overview of the Analysis
Maria, the Chief Data Scientist for City School System has tasked me to help her prepare all standardized test analysis to look into performance trends and patterns. These insights will be used to inform discussions and strategic decisions at the school. By analyzing data on student funding and standardized test schools, we can showcase trends in school performance to assist the School Board and Superintendent in making decisions for budgets and priority. 

After our initial analysis, we were notified that there was evidence of academic dishonestly with the reading and math hscores for the Thomas High School 9th graders. In order to uphold state-testing standards, we had to replace their math and reading scores with nulls and give a report on the updates.

## Results

### How is the district summary affected?

The performance of the district went down slightly, as shown in the two images. The overall percentage passing went down from 65% to 64.9%. 

District Summary Original
![District Summary Revised](https://github.com/chloebellehooton/School_District_Analysis/blob/main/Images/district_summary_before.png)

District Summary Revised
![District Summary Revised](https://github.com/chloebellehooton/School_District_Analysis/blob/main/Images/district_summary_after.png)


### How is the school summary affected?
The changes for the Thomas High School summary from the original to the final product:  
  - Average Math Score: decreased from 83.42 to 83.35
  - Average Reading Score: increased from 83.85 to 83.90
  - % Passing Math: decreased from 93.27 to 93.19
  - % Passing Reading: decreased from 97.31 to 97.02
  - % Overall Passing: increased from 90.95 to 90.63

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

School Summary Original
![School Summary Original](https://github.com/chloebellehooton/School_District_Analysis/blob/main/Images/per_school_summary_before.png) 

School Summary Revised
![School Summary Revised](https://github.com/chloebellehooton/School_District_Analysis/blob/main/Images/per_school_summary_after.png)

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade


#### Scores by School Spending, Size, and Type
Comparing the orignal and the revised scores by spending, size, and type, they have not changed after removing the academic dishonesty cases. These numbers have also been rounded so perhaps there is a slight difference but it would not be significant at the aggregate level. 

#### School Size
Scores by School Spending Original
![Scores by School Spending Original](https://github.com/chloebellehooton/School_District_Analysis/blob/main/Images/scores_spending_before.png)
Scores by School Spending Revised
![Scores by School Spending Revised](https://github.com/chloebellehooton/School_District_Analysis/blob/main/Images/scores_spending_after.png)

#### School Size
Scores by School Size Original
![Scores by School Size Original](https://github.com/chloebellehooton/School_District_Analysis/blob/main/Images/scores_size_before.png)
Scores by School Size Revised
![Scores by School Size Revised](https://github.com/chloebellehooton/School_District_Analysis/blob/main/Images/scores_size_after.png)

#### School Type
Scores by School Type Original
![Scores by School Type Original](https://github.com/chloebellehooton/School_District_Analysis/blob/main/Images/scores_type_before.png)

Scores by School Type Revised
![Scores by School Type Revised](https://github.com/chloebellehooton/School_District_Analysis/blob/main/Images/scores_type_after.png)

## Summary: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


After replacing the reading and math scores with NaNs, the average reading scores and overall pass percentage increased and the average math scores, math pass percentage, and reading pass percentage decreased. The scores by school type, size, and spending did not change. 
