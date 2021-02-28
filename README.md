# School_District_Analysis
Josafath Pelayo
2/28/2021

## Overview of the School Disctrict Analysis
The purpose of this analysis is to analize 15 schools in a school district that has 39,169 students. The data file used for this analysis is "students_complete.csv" which has each student based on there gender, grade, school they attend, and reading/math scores. The other csv file used is named schools_complete.csv, which shows the 15 school based on school type, whether it's a charter or district, the size of the school based on students who attend, and the budget of each school. Knowing this, the analysis highliights a high level snapshot of the district's key metrics, and an overview of the key metrics for each school, presented in a table format. Along the analysis, Thomas High School 9th graders had to be taking out of the overall analysis as there was academic dishonesty for their tests scores. In doing so, the Thomas High School student's scores were replaced with NaNs while keeping the rest of the data intact.The end results shows the following:
top 5 and bottom 5 performing schools, based on the overall passing rate, the average reading and math score received by students in each grade level at each school, and  school performance based on the budget per student, the school size, and type of school.


## Results
- The school district summary was affected by a little bit as pulling out the 9th  graders at Thomas caused.
    - Avereage math score was 78.9 without the dishonest students compared to 79 with the 9th graders included.
    - Avereage reading score, 81.9 stayed the same for both old data and new data without the 9th graders included.
    - Passing math percenatge was 74.8% without the dishonest students compared to 75% with the 9th graders included.
    - Passing reading percenatge was 85.7% without the dishonest students compared to 86% with the 9th graders included.
    - Overall passing percenatge was 64.9% without the dishonest students compared to 65% with the 9th graders included.
- The school Summary for only Thomas High  was greatly effected by taking out the the 9th graders. 
    - Avereage math score was 83.35 without the dishonest students compared to 83.4 with the 9th graders included.
    - Avereage reading score, 83.89 without the dishonest students compared to 83.84 with the 9th graders included.
    - Passing math percenatge was 66.91% without the dishonest students compared to 93.27% with the 9th graders included.
    - Passing reading percenatge was 69.66% without the dishonest students compared to 97.3% with the 9th graders included.
    - Overall passing percenatge was 65.07% without the dishonest students compared to 90.94% with the 9th graders included.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Replacing the ninth graders' math and reading scores affected Thomas High School's performance by having an overall lower passing perecentage (65.07%) compared to 90.94% in the school summrary chart. 
    - Interestingly, when one looks at the school summary chart, Thomas High becomes one of the lowest performing schools but still considered the top 5 schools if you take the statics for 10, 11 and 12 graders only. 
- Replacing the ninth-grade scores affect the following:
    - It only affected math and reading scores for the 9th graders in Thomas High [Math_by_Grade](   ), [Reading_by_Grade]()
    - It didn't affect scores by school speind as spending ranges per school stayed in the same range, $630-$644 [Scores_by_School_Spending](   )
    - It didn't affect scores by school size as Thomas high is still categoriezed as medium with 1000-2000 [Scores_by_School_Size](  )
    - It didn't affect scores by school type as it had the same output
# Summary
Overall, by replacing the 9th graders scores at Thomas High School with NaNs, it greatly effected the school summary data chart beacause the whole 9th grade scores were dropped.
This caused the avereage math score to slightly increase from 83.4 to 83.35, avereage reading score to slightly increase from 83.84 to 83.89 .The drastic changes were seen in passing math percentage from 93.27% to 66.91%, passing reading percenatge from 97.3% to 69.66%, and overall passing percentage from 90.94% to 65.07%. If we just look at the school summary chart with all 15 schools, the Thomas High School would be taking out of the top 5 schools and be put into the last top 5. When we look at the rest of our data analysis, scores by school spending, scores by school size, scores by school type where not affected? How does this make sense if the school summary chart says otherwise? The reason behind this is that we did exclude the ninth graders which is seen in the math and reading scores by grade, but the rest of the Thomas High School graders did great in there scores. Due to this, Thomas High School was still be able to be one of the top schools as we only include 10-12 gradders in the rest of the analysis after school summary. 
