# School_District_Analysis
## Overview of the school district analysis
The purpose of this analysis is to analyze the difference between standardized testing scores within a school district after removing bad information within the dataset.
## Results
- The district summary was affected in various ways after fixing the dataframes, but the results did not change by a significant amount. The total student count did decrease a small amount, however the testing results and the percentage of students passing the subjects did not change significantly.
  - Original District Results
   
   ![School District Original Results](Resources/district_summary_df_results_bad_data_1.PNG)
  - Adjusted District Results
    ![School District Adjusted Results](Resources/district_summary_results_df_fixed_data.PNG)
- The school summary was not affected in a significant way by removing the test scores of the 9th graders and adjusting the amount of students.
  - Original School Results
    ![School Summary Original Results](Resources/per_school_summary_df_results_bad_data.PNG)
  - Adjusted School Results
    ![School Summary Adjusted Results](Resources/per_school_summary_df_results_fixed_data.PNG)
- Replacing the ninth graders’ math and reading scores did not affect Thomas High School’s performance relative to the other schools in a significant manner. The mean's and percentages did not show significant variance.
- When we replace the ninth grade scores, it only affects the 9th grade cell for reading and math scores. All the other scores stay the same.
  - Original Math Results by Grade
    
    ![Math Results by Grade Original](Resources/math_scores_by_grade_bad_data.PNG)
  - Original Reading Results by Grade
    
    ![Reading Results by Grade Original](Resources/reading_scores_by_grade_bad_data.PNG)
  - Adjusted Math Results by Grade
    
    ![Math Results by Grade Fixed](Resources/math_scores_by_grade_fixed_data.PNG)
  - Adjusted Reading Results by Grade
    
    ![Reading Results by Grade Fixed](Resources/reading_scores_by_grade_fixed_data.PNG)
- Scores by school spending was not affected by replacing the 9th grade scores.
  - Original Scores by Spending
  
    ![Score by School Spending](Resources/scores_by_school_spending_bad_data.PNG)
    
  - Adjusted Scores by School Spending
    
    ![Adjusted Scores by Spending](Resources/scores_by_school_spending_fixed_data.PNG)
- Scores by School size were also not affected by replacing the 9th grade scores.
  - Original Score by School Size
  
    ![Original Score by School Size](Resources/score_by_school_size_bad_data.PNG)
  - Adjusted score by School Size
  
    ![Adjusted Score by School Size](Resources/score_by_school_size_fixed_data.PNG)
- Scores by school type was also not affect by replacing the 9th grade scores.
  - Original Scores by School Type
    
    ![Original score by school type](Resources/scores_by_school_type_bad_data.PNG)
  - Adjusted Score by School type
    
    ![Adjusted score by School Type](Resources/scores_by_school_type_fixed_data.PNG)
## Summary
I did not find major changes to the results when we removed the 9th grade students results. The only things that really changed was the number of students we were counting. From there, the data shows that the majority of results stayed pretty much the same. The overall passing percentage in Thomas High School, but it was less than 1%, so it was not a significant amount. All in all, it looks like removing the 9th grade results did not affect the findings in a significant manner.
