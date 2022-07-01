# School_District_Analysis

## Overview of the School District Analysis project

I have performed analysis on the student funding, school performance, and grades on standardized testing in order to help the school board make decisions regarding school budgets and priorities. However, there seems to be evidence of academic dishonesty in the school reporting for Thomas High School ninth graders. The school board want sto uphold state-testing standards so I have been asked to replace the math and reading scores for Thomas High School ninth graders with NaNs while keeping the rest of the data intact. Once replaced, I will repeat the school district analysis that I did describe how these changes affected the overall analysis.


## Results


- How is the district summary affected?

Replacing Thomas High School ninth graders' scores with NaN didn't impact district analysis much. Percentages didn't change more than 0.5 percentage points per category. Categories consists of average math and reading scores as well as percent passing math, reading, and both (overall).

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The ranking of the top schools were not affected by the update. Thomas High School remained in the top two schools based on overall passing percentage. 

- How does replacing the ninth-grade scores affect the following:

   - Math and reading scores by grade
   In both the Math Scores by Grade dataframe and the Reading Scores by Grade dataframe, the only different value is the NaN value for 9th grade Thomas High School Students
   - Scores by school spending
   Scores by school spending didn't change at all when looking at the final formatted dataframe. This means any changes to the numbers were less than 0.1%.
   - Scores by school size
   Scores by school size also didn't change at all when looking at the final formatted dataframe. This means any changes to the numbers were less than 0.1%.
   - Scores by school type
   Scores by school type also didn't change at all when looking at the final formatted dataframe. This means any changes to the numbers were less than 0.1%.
  
## Summary 

In summary, addressing the academic dishonesty in the Thomas High School ninth grade metrics did not impact the analysis much at all. Changes in the district summary were less than 0.5 percentage points. The ranking of the schools by overall passing percentage were unchanged. Changes in scores by school spending, school size, and school type had differences of all less than 0.1%. 

