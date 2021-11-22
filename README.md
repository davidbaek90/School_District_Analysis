# School_District_Analysis

## Overview of School District Analysis

### Purpose

#### The purpose of the School District Analysis is to help the school board analyze the math and reading score data of schools in the district without the suspecious score data from Thomas High School.

## Results

#### How is the district summary affected?
- In this part of the analysis, reading and math scores of all grade 9 students at Thomas High School was formatted with Nan. The two tables below show the origina vs adjusted result of the district summary. The adjusted analysis show that, compared ot the original data, "Average Math Score" dropped by 0.06%, "Average Reading Score" dropped by 0.02%, "% Passing Reading" dropped by 0.15% and "% Overall Passing" dropped by 0.31%. The original and adjust data is coherent since the number of grade 9 student at Thomas High School only makes up 461 students out of 39,170 students that represent the whole district.

<p align="center">
<b>District Summary - Original</b>
    <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/district_summary_before.JPG">
</p>
<p align="center">
<b>District Summary - Adjusted</b>
    <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/district_summary_after.JPG">
</p>

#### How is the school summary affected?
- After analyzing the data, Thomas High School displayed a significant reduction in percentage of students passing math (93.27 to 66.91%), passing reading (97.31 to 69.66%), and passing overall (90.95 to 65.08%). On contrary, Average math and reading scores for Thomas High School did not fluctuate significantly, indicating reduction in hundredth decimal value scale. Student grade data for other schools did not change after data was adjusted. The DataFrame for the original vs adjusted school summary is shown below.

<p align="center">
<b>School Summary - Original</b>
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/school_summary_before.JPG">
</p>
<p align="center">
<b>School Summary - Adjusted</b>
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/school_summary_after.JPG">
</p>

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- As shown in above School Summary charts (Original vs THS 9th removed), removing the 9th grade reading and math scores did not affect it's placement in the school ranking in overall passing percentage. Overall passing percentage for Thomas High School went down from 90.95% to 90.63%, which was not significant enough to hand its 2nd place over to Griffin High School.

<p align="center">
<b>School Summary - Adjusted</b>
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/top_ten_summary_before.JPG">
</p>

<p align="center">
<b>School Summary - Adjusted with THS 9th Grade Removed</b>
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/top_ten_summary_after.JPG">
</p>

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
- The original math and reading scores by grade is shown on the left side of the pictuers, and 0th grader removed (adjusted) math and reading scores are shown on the tables to the right. As expected, only 9th grade math and reading scores are replaced with "NaN's"

<p align="center">
<b>Math Scores by Grade - Original(Left), 9th Grader Removed(Right)</b>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/math_score_by_grade_before.JPG">
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/math_score_by_grade_after.JPG"> 
</p>

<p align="center">
<b>Reading Scores by Grade - Original(Left), 9th Grader Removed(Right)</b>
</p>
<p align="center">  
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/reading_score_by_grade_before.JPG">
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/reading_score_by_grade_after.JPG">
</p>
  
#### Scores by school spending
- The adjusted data with 9th grader removed for Thomas High School affected the scores for $630 - $644 spending range. However the change is merely in hundredth decimal place scale, which is insiginificant.

<p align="center">
<b>Scores by School Spending - Original(Above), 9th Grader Removed(Below)</b>
</p>
<p align="center">  
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/scores_by_school_spending_before.JPG">
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/scores_by_school_spending_after.JPG">
</p>

#### Scores by school size
- Once again, the change in the scores and passing percentages are insignificant after 9th grade data is removed, as shown below. Overall Passing percentage for medium sized class was reduced from 90.62 to 90.56% after 9th grader data from Thomas High School was removed.
  
<p align="center">
<b>Scores by School Size - Original(Above), 9th Grader Removed(Below)</b>
</p>
<p align="center">  
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/scores_by_size_before.JPG">
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/scores_by_size_after.JPG">
</p>

#### Scores by school type
- Lastly, before and after data of scrores by school type shows similar battern. Thomas High School is a Charter school type, which explains the small reduction of scores and passing percentages.

<p align="center">
<b>Scores by School Type - Original(Above), 9th Grader Removed(Below)</b>
</p>
<p align="center">  
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/scores_by_type_before.JPG">
  <img src="https://raw.githubusercontent.com/davidbaek90/School_District_Analysis/main/Resources/scores_by_type_after.JPG">
</p>

## School District Analysis Summary
- Distict Analysis - Average math/reading scores and Percentage passing math/reading went down but in insignificantly amount. Overall passing student for both reading and math changed by -0.31% from 65.17% to 64.86%
- School Analysis - Thomas High School rained 2nd highest ranked school in overall student passing percentage for math and reading. This is unchanged after the 9th grade data was replaced. Overall passing percentage changed by -0.12% from 90.95% to 90.63%
- Reading Scores by Grade - After 9th grade date for Thomas High School was repalced, dataframe value for 9th grade at Thomas High School now displays "Nan".
- Sores by school Spending/Size/Type - Change of average math/reading scores, as well as passing percentage was insignificantly. Changes were reflected only in the ranges that Thomas High School represented ($630-644 spending range, 1000-2000 school size, and Charter school type).
