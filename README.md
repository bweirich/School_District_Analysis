# School_District_Analysis
Python/Jupyter Notebook

## Overview
The School District has collected data regarding stadardize test scores and student funding.  This analysis will help identify trends on school performance and budget allocations as well as other metrics.

### Purpose
The purpose of this analysis is to review the stadardized test scores for each grade at each school in the district with regards to the schools metrics.  These metrics include the student grade level, school size, school budget, and type of school.  This analyis will also take into account the and adjust for corrupted test scores.  This insight will help inform the school district for future decisions.

## Results
When first doing the analysis it was discovered that there are corrupted test scores for 9th graders at Thomas High School.  The following results show how the analysis is affected when the corrupted test scores are removed.  The KPI analysis is shown below before and after these scores where eliminated. 

### District Summary
- The original District Analysis shows the following results:
![alt text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Original_District_Summary.png)
- The adjusted District Anlaysis after the Thomas High School 9th grade test scores where removed show the following results:
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/District_Summary.png)
- From this you can see a decrease in the percentage of passing scores although the amount it decreases by is not a significant decrease and is less than 1%.

### Ranking of Schools Overall Passing Percentage
- The original ranking of Thomas High School based on Percentage of Overall Passing scores was second with scores of 91.33% as seen below:
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Original_Top_Schools.png)
- The adjusted ranking of Thomas High School based on Percentage of Overall Passing scores did not change with scores of 90.6% as seen below:
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Top_Schools.png)
- Although the overall passing percentage was affected by the removal of the 9th grade scores for Thomas High School the overall ranking with regards to other schools in the district did not change.

### Math & Reading Scores by Grade
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Original_Math_by_Grade.png)
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Math_by_Grade.png)

### Scores by School Spending
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Original_Spending_Summary.png)
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Spending_Summary.png)

### Scores by School Size
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Original_Size_Summary.png)
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Size_Summary.png)

### Scores by School Type
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Original_Type_Summary.png)
![alt_text](https://github.com/bweirich/School_District_Analysis/raw/main/Resources/Type_Summary.png)
