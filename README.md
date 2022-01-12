# School_District_Analysis
Python, Anaconda
## Project Overview
The local school board requested analysis of the district's school performance. The school performance included reading and math scores for the district high schools, passing scores, school budgets and spending per pupil. During the analysis, it was discovered that the scores of the ninth grade students in the Thomas High School may be adulterated. The analsys was repeated. This report includes comparisons of performance before and after excluding the erroneous scores.  

## Project Resources

The source data files were provided by the district.

This audit was perfomed using Python 3.7 and Anaconda which enabled the use of Jupyter Notebook. 

## Project Results
Analysis of the district performance metrics showed that the exclusion of a small number of suspect scores from the ninth graders at Thomas High School did not change the overall passing percentage for the district.  
The district summary report including the ninth graders from Thomas High school was:
- [Header](https://github.com/Bscheinin/School_District_Analysis/blob/main/Resources/Summary%20header.PNG)
Without the scores of those students, the new district summary report is:

However, the Thomas High School summary scores increased dramatically when the ninth grade scores were excluded:

School ranking within the district also changed when the ninth graders scores were excluded:

Finally, the scores by school spending, school size and school type were all negatively effected when the ninth grade scores for Thomas High School were included in the analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
