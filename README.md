# School_District_Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.
### Purpose: 
Maria and her supervisor said that the previous file showed evidence of academic dishonesty. We have been asked to replace the 9th grade Thomas High School math and reading scores with Nan's in the data and to re-run the analysis. 

### Results:

How is the district summary affected?
- Overall Passing Percentage: went down .2%
- Passing Math % and Passing Reading % both went down by approximately .1%

How is the school summary affected?
At Thomas High School the following changes occurred as a result of removing all 9th grade math and reading scores:
- % Passing Math up 26%
- % Passing Reading up 27%
- % Overall Passing up 25%

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Performance in all categories(reading and math) increases significantly 
- Thomas High School went from one of the worst performing high schools to one of the highest performing high schools 

How does replacing the ninth-grade scores affect the following:

Math Scores by Grade

![mathscores_bygrade](https://user-images.githubusercontent.com/84742544/125677706-758f0c37-0f44-4331-b99d-91c36940c629.PNG)

Reading Scores by Grade

![readingscores_bygrade](https://user-images.githubusercontent.com/84742544/125677707-b70b3b42-d9fd-4bd3-9bfa-53e325a79d90.PNG)

Scores by school spending

![results_schoolspending](https://user-images.githubusercontent.com/84742544/125677703-68fdfcb8-4fae-442b-80d6-377a3dcb6433.PNG)

Scores by school size

![results_schoolsize](https://user-images.githubusercontent.com/84742544/125677700-50f3da65-cad7-4396-b1fb-e9158ad2387a.PNG)

Scores by school type

![results_schooltype](https://user-images.githubusercontent.com/84742544/125677705-cc0b6397-4ebf-4c94-8154-1b1402868a12.PNG)

## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Performance across all categories at Thomas High School increases significantly(more than 25% in most categories). I would infer that the 9th grade scores carried the large majority of low test scores for the school.  

Because of the above point, I would recommend further analysis into Thomas High School and specifically into the removed 9th grade scores. I would want to confirm a large number of low scores pulling the school averages down, just to confirm the inference above and to double-check that there isn't an anomaly within the data or in our previous analysis. 

Analysis in performance by school size, school type and school spending varied very little. This is because the removed 9th grade scores from Thomas High School made up only apprioximately 1.5% of test scores district wide. 

Average test scores and passing percentages across the district show little change from removing the scores. This is because the small number of records ~461 scores in each category that were removed out of the approximately 30,000 across the district. 
