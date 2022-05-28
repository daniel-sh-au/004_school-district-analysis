# Module 4: PyCitySchools with Pandas

## Overview of the School District Analysis

### Summary
Due to the presence of academic disloyalty, the math and reading scores of ninth graders at Thomas High School must be considered null. The purpose of this analysis was to remove the scores for ninth graders in Thomas High School while keeping the other scores untouched. Then, the school district analysis was repeated to observe the changes on the analysis.  

### Resources
* Software: Jupyter Notebook, Python 3.7.13,
* Data Sources: [schools_complete.csv](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/schools_complete.csv), [students_complete.csv](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/students_complete.csv)
* Challenge Code: [PyCitySchools_Challenge](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/PyCitySchools_Challenge.ipynb)

## Results
* The district summary was affected marginally. As shown below in the old and new district summaries, the scores and percentages decreased around 0.0 to 0.3. This slight disparity was caused by the removal of only 461 students (THS, 9th graders) of the 39,170 total students in the data set. 
  * Old District Summary: ![District_Summary_Old](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_district_sum_old.PNG)
  * New District Summary: ![District_Summary_New](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_district_sum_new.PNG)

* The school summary for Thomas High School was also affect marginally. Shown below in the old and new THS summary, the scores and percentages mostly decreased at a maximum of roughly 0.35. Notably, the average reading score increased by approximately 0.05. Like the district summary, this change is slight because only a small population of the total population was altered. 
  * Old School Summary: ![School_Summary_Old](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_school_sum_old.PNG)
  * New School Summary: ![School_Summary_New](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_school_sum_new.PNG)

* In comparison with the other schools, replacing the ninth grader’s math and reading scores did not affect the school’s rank. As shown below, Thomas High School continues to be ranked second. 
  * Old Top 5: ![Top_5_Old](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_top5_old.PNG)
  * New Top 5: ![Top_5_New](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_top5_new.PNG)

After replacing the ninth-grade scores for Thomas High School (THS):
* The math and reading scores for ninth graders at THS were replaced with nan. All other grades, which include grades 9-12 for every other school and grades 10-12 for THS, remain unchanged. Below are the old and new math scores by grade. 

  | Old Math Score by Grade | New Math Score by Grade |
  | ----------------------- | ----------------------- |
  | ![Score_by_Grade_Old](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_score_by_grade_old.PNG)| ![Score_by_Grade_New](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_score_by_grade_new.PNG) |

* The scores by school spending did not change significantly. In the results, the old and new scores by school spending are the same, to the tenths decimal place. The image links to the old and new score by school spending are below: 
  * Old Score by School Spending: [Score_by_Spending_Old](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_score_by_spending_old.PNG)
  * New Score by School Spending: [Score_by_Spending_New](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_score_by_spending_new.PNG)

* The scores by school size did not change significantly. In the results, the old and new scores by school size are the same, to the tenths decimal place. The image links to the old and new score by school size are below: 
  * Old Score by School Size: [Score_by_Size_Old](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_score_by_size_old.PNG)
  * New Score by School Size: [Score_by_Size_New](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_score_by_size_new.PNG)

* The scores by school type did not change significantly. In the results, the old and new scores by school type are the same, to the tenths decimal place. The image links to the old and new score by school type are below: 
  * Old Score by School Type: [Score_by_Type_Old](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_score_by_type_old.PNG)
  * New Score by School Type: [Score_by_Type_New](https://github.com/daniel-sh-au/UofT_DataBC_Module04_school-district-analysis/blob/main/Resources/results_score_by_type_new.PNG)

## Summary
The removal of the ninth grader scores in Thomas High School (THS) had some impacts on the dataset. In the school summary, it was observed for THS that the **average math score decreased** by approximately **0.07%**. It was also observed for THS that the **average reading score increased** by approximately **0.05%**. Additionally, THS’s **% Passing Math, % Passing Reading, and % Overall Passing decreased** by **0.09 to 0.32%**. These decline of scores from THS lead to a reduction in the **District Summary, score and percent passing columns**; A decrease of approximately **0 to 0.3%**. Aside from the School Summary and District Summary metrics, no other changes were found in the school district analysis. Ultimately, these changes are minor and demonstrates that the removal of 461 students from the 39,170 total student population will not drastically affect the analysis. Thomas High School continues to be ranked second out of all the high schools in the district. 
