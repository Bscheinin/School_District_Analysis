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
![Original District Summary](https://github.com/Bscheinin/School_District_Analysis/blob/main/Resources/Original%20District%20Summary.PNG)

Without the scores of those students, the new district summary report is:
![New District Summary](https://github.com/Bscheinin/School_District_Analysis/blob/main/Resources/New%20District%20Summary.PNG)


However, the Thomas High School summary scores increased dramatically when the ninth grade scores were excluded.

Here are the original Thomas High School Summary followed by the new THS summary with the ninth grade scores excluded:
![Header](https://github.com/Bscheinin/School_District_Analysis/blob/main/Resources/Summary%20header.PNG)
![Original THS Summary](https://github.com/Bscheinin/School_District_Analysis/blob/main/Resources/Original%20THS%20summary.PNG)

![Header](https://github.com/Bscheinin/School_District_Analysis/blob/main/Resources/Summary%20header.PNG)
![New THS Summary](https://github.com/Bscheinin/School_District_Analysis/blob/main/Resources/New%20THS%20Summary.PNG)

School ranking within the district also changed when the ninth graders scores were excluded. Thomas High School moved up in the district rankings. The overall 9th grade scores for the district also increased when the suspect scores were excluded from the analysis.

Finally, the Medium school size and Charter school type categories were all negatively effected when the ninth grade scores for Thomas High School were included in the analysis. The performance score by spending per child was relatively unchanged based on the small number of students that were excluded.

## Summary
The four changes noted in the updated school district analsys after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs were:
- The passing reading and math scores for Thomas High School as well as the overall passing score increased dramatically.
- Thomas High School moved up in the district rankings based on the overall percentage of passing students.
- The performance scores for the Medium size school category increased.
- The reading and math passing scores increased for the Charter school type.

It is unclear the motive for the adulerated ninth grade performance scores. By excluding these suspect scores, the performance of Thomas High School compared to the rest of the district schools could be evaluated. Fortunately, given the size of the school in relation to the total district population (4% of the district), these erroneous scores did not effect the overall district summary.
