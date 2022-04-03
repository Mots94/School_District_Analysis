# School_District_Analysis
![class](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/school.png)
## Using Python to analyze standardized test scores

## Overview
The analysis of school data is often crucial to determine the district's allocation of yearly school funds.  In this analysis, factors such as average math and reading scores, and percentage of students passing math and reading were compared to school budget, school size, and school type. The purpose of this analysis was to provide the district school board with a multi-level report of district and individual school performance.  The school board would like to know more about the top and bottom performing schools to determine if adjustments need to be made to the yearly school budget.  After completing this report for the school board, it was discovered that Thomas High School had altered test scores for 9th grade students.  As a result, all 9th grade test scores had to be dropped from this analysis, and all metrics were revised to reflect this change. 

## Results
* There are no changes to the the nubmer of total schools, total students, or total budget between the original district analysis and revised district analysis.  There is a change to the average math score for the district, but it is small.  The original average score was 79.0, and changed to 78.9 after revision.  There is a change in percentage of students passing math, reading, and a combination of math and reading as well.  That is displayed in the outputs below:

#### Original District Analysis
![ODA](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/district_analysis_original.PNG)
#### Revised District Analysis
![RDA](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/district_analysis_revised.PNG)
---
* Furthermore, reading and math scores for Thomas High School did change for the individual school analyses after data set revision.  In the original analysis, the average math score for Thomas High School was 83.42, and dropped to 83.35 in the revised analysis.  Reading scores actually increased from an average of 83.85 to 83.90.  There was also a change in percentages of students passing math, reading, and math and reading.  In all cases, the percentage of students passing one or both subjects decreased from the original analysis to the revised analysis.  No other schools' data was affected by eliminating Thomas High School's 9th grade data.

#### Original Per School Analysis
![OSA](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/school_analysis_original.PNG)
#### Revised Per School Analysis
![RSA](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/school_analysis_revised.PNG)
---
* As far as their perfomance, Thomas high school does not change very much relative to other schools.  In both the original and revised analysis, Thomas High School is still the number two school for overall percentage of students passing math and reading.  Thomas High School's percentage of students passing reading and percentage passsing math and reading both decrease about .3% from the original analysis to the updated analysis.  This does bring Thomas High School closer to the the number three spot overall in the district, as the current number three school, Griffin High School, has about a 90.6% overall passing rate compared to Thomas' overall passing rate of 90.63%.  The percentage of students passing reading and math was higher for Thomas in the original analysis, putting them closer to the number one schoool, Cabrera High School. 

#### Original Top Schools Analysis
![OTS](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/original_top_schools.PNG)
#### Revised Top Schools Analysis
![RTS](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/revised_top_schools.PNG)
---
* Each grade level had its average scores calculated separate from one another, so not including the ninth-grade reading and math scores did not affect those other average scores.Other schools and all other grades were not affected by the removal of Thomas' 9th grade data.

#### Original Math and Reading Scores by Grade
![OMRS](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/original_math_by_grade.PNG) ![OMRS2](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/original_reading_by_grade.PNG)
#### Revised Math and Reading Scores by Grade
![RMRS](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/revised_math_by_grade.PNG) ![RMRS2](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/revised_reading_by_grade.PNG)

* In the school spending analysis, four bins were created based on school spending per student.  The four bins were <$586, $586-630, $631-645, and $646-675.  Thomas High School fell into the $631-645 bin. They are the only school with score data that changed, so that is the only spending bin that saw a performance difference.  In the original analysis, that bin had an overall student passing rate of 62.86%.  In the revised analysis, there was a decrease to 62.78%.  This can be seen in the following output:

#### Original Spending Bins Analysis
![OSB](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/original_spending_bins.PNG)
#### Revised Spending Bins Analysis
![RSB](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/revised_spending_bins.PNG)
---
* Similar to the groupings done by student spending, the grouping by school size analysis saw scores change between the original and revised analysis.  There was a decrease in raw scores as well as passing percentages for students in the "Medium School" category.  The "Medium School" category was defined as any school with a student count from 1000 to 1999.  Since Thomas High School has 1635 students, they fall squarely in that category.  This is the reason we see a decrease in pass rates for medium sized schools.

#### Original School Size Analysis
![OSS](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/original_school_size.PNG)
#### Revised School Size Analysis
![RSS](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/revised_school_size.PNG)
---
* Thomas High School is classified as a Charter school, so in the school type analysis there are mean score and percent passing changes.  Overall, from the original analysis to the revised analysis there are decreases to average math scores, percent passing reading, percent passing math, and percent passing math and reading.  Average reading scores for charter schools increased slightly.  

#### Original School Type Analysis
![OST](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/original_school_type.PNG)
#### Revised School Type Analysis
![RST](https://github.com/Mots94/School_District_Analysis/blob/main/Resources/revised_school_type.PNG)

## Summary
The replacement of all ninth-grade scores for Thomas High School did change some analysis results at the district level and indidivudal school level.  In the revised district analysis, the biggest change seen was a decrease of percentage of students passing overall.  This can be seen by a decrease of .3% after revision.  As a whole, this is not a huge change compared to the number of students in the district.  It equates to about a 100 student decrease for overall passing.  

---
In the original school analyses, it was also observed that Thomas High School had decreased metrics for everything except average reading scores.  The average reading score increased by about .15, even after revision of the ninth-grade scores.  If I was to take an educated guess, I would say there were many students in the Thomas ninth-grade class with reading scores close to the passing grade, but fell short.  If these scores were unjustly rounded or changed to just be passing, this could significantly increase the passing percentage, and still pull the average reading scores down.  

---
Although Thomas High School's position in the top five schools did not change after analysis revision, we did see that their passing percentages were much closer to the number three school.  Originally, Thomas High School's passing percentages were fairly close to the number one school.  The number one school in the district, Cabrera High School, does have a higher budget than Thomas High School.  Perhaps Thomas High School was changing their test scores in order to justify requests to the school board for a higher yearly budget.