# School District Analysis

# Overview:
Analysis of data for the City School System, to aggregate and, find patterns and insights in standardised testing and school performance so that the superintendent and school district can make strategic decisions regarding budgeting and allotment at the district and school level. 

We have been that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. So we will have to remove the grades for Thomas High School - ninth graders. 

Maria, the City School Systems chief data scientist wants the analysis to include the following 
* District Summary
* School Summary
* High and Low Performing Schools
* Math and Reading Scores by Grade
* Scores by School Spending¶
* Scores by School Size
* Scores by School Type

### Resources
* Data Source: 
    1. School Funding : schools_complete.csv
    2. Standardized Testing : students_complete.csv
* Software: Python 3.8.8, Pandas Dataframe

# Results: 
### How is the district summary affected?
There is no significant difference for the district summary for the average scores or percentages in the following tables. 
![4E1B0FD3-17BC-41C5-9501-28780904CBC3_4_5005_c](https://user-images.githubusercontent.com/75961057/142272751-5d5935bb-6339-4f87-9f6a-91f663bd16bd.jpeg)

### How is the school summary affected?
There was a significant change in Thomas High School summary after removing Thomas High School 9 grader scores but that was solved by substituting the agrregate scores and percentages for 10th, 11th and 12th graders in the Thomas High School Summary line. So the final school summary shows only the aggregate values for grades other than 9th for Thomas High School. 

Thomas High School Summary after 9th grade was removed
![Thomas High School Original](https://user-images.githubusercontent.com/75961057/142271971-70ac1a2e-11ac-44d4-ac65-7f6958f7bd7f.png)

Per School Summary
![Per School Summary](https://user-images.githubusercontent.com/75961057/142272879-35d9787f-3374-444f-b567-ad7e68b9bd7c.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
As you can see from the image below, Thomas High School was affected with a drop from 90% to 65% in the overall percentage. This affects the schools statistics significantly which inturn will affect a decrease in the school budget from the district and subsequently the district budget from the state. The analysis will also be wrong as only 10th, 11th and 12th graders for Thomas High School are to be included in the analysis. This was solved by substituting the agrregate scores and percentages for 10th, 11th and 12th graders in the Thomas High School Summary line. 

![4DF0BC94-D76E-405E-91B6-B6598E5B500B_4_5005_c](https://user-images.githubusercontent.com/75961057/142273966-8c38c007-4e46-444e-9bed-770bab8ebde0.jpeg)

### How does replacing the ninth-grade scores affect the following:
These were the scores of Thomas High School before replacing with agrregate scores and percentages for 10th, 11th and 12th graders in the Thomas High School Summary line. 
![Thomas High School Original](https://user-images.githubusercontent.com/75961057/142276204-7a158319-6e27-4ea5-ad96-dc1210c37038.png)
And these are the score after replacing with aggregate values. 
![Screen Shot 2021-11-17 at 11 35 20 AM](https://user-images.githubusercontent.com/75961057/142276322-224ca7f3-16a0-45bc-bed0-f613fd059085.png)

Math and reading scores by grade : You see a big difference in the % Passing and % Overall Passing scores from ~90% to ~ 65%. These values will skew the results for making decisions. 
Scores by school spending
Scores by school size
Scores by school type

![Final per school summary](https://user-images.githubusercontent.com/75961057/142277002-27ca2d1c-1507-49e3-a6de-e030f09f100d.png)



Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
