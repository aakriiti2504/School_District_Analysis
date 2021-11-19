# School_District_Analysis
This analysis consists of two technical deliverables and written report to present the results on the ninth grade reading and math scores and  perform school district analysis. 


## Background: 

Maria, the chief data scientist for a city school district is responsible for analyzing information from a variety of resources and in a variety of formats. In this role she has a task of preparing all standardized test data for analysis, reportings and presesntation to provide insights about performance trends and patterns. These insights are used for informed discussions and strategic decisions at the school and district level. 

## Overview of the school district analysis:

I will be helping Maria analyze data on student funding and students standardized test scores. I am given access to every student's math and reading scores, as well as various information on the schools they attend. My task is to aggregate the data and showcase trends in school performance. This analysis will assist the school board and the superintendent in making decisions regarding the school budget and priorities. For this task, the Family Educational Rights and Privacy Act(FERPA) of 1974 is taken into consideration as it protects the  privacy of student education records. This law applies to all school that receive funds under an applicable program of the US Department of Education. The data is to be treated with utmost confidentiality to protect the students I am reporting on. 

## Tools used:

Maria advises to download and install a software calle Anaconda, a free open source distribution software for over 1500 packages, to perform the analysis. She has also provide some instructions and video tutorials. The analysis of school data will be done using the package 'Jupyter Notebook'.Jupyter Notebook is to Anaconda what Microsoft Word is to Microsoft Office. Anaconda packages support the Python and R programming languages for datatscience, machine learning and data processing and so on. Here we will be using Python too.
Data source - election_results.csv file is an Excel file with given data.
- Software - Python 3.7.8, Visual Studio Code, Anaconda, Jupyter Notebook
- Data Source - PyCitySchools.ipynb
- Libraries - Pandas
- Add,commit,push - GitBash and GitHub

## Purpose:
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty. It has been noted that the reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. Maria in turn has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once replaced, Maria would like me to repeat the school district analysis  and write up a report to describe how these changes affected the overall analysis. For this purpose, the following steps were taken to work on the given starter data:
- In order to select all the math and reading scores from Thomas High School, the loc method was used.
- In order to retrieve all the rows with 'Thomas High School' and '9th grade' entries, the comparison operator was used.
- The reading and math scores were also retrieved using logical and comparison operators.
- The reading and math scores were then replaced by 'NaN' so that such entries will not be considered for calculation in the school district summary.
 
![15](https://user-images.githubusercontent.com/23488019/142519175-45dab3df-1bea-4263-88c2-72e4ecbda380.PNG)
## Code Snapshots of the Deliverables:
![22](https://user-images.githubusercontent.com/23488019/142552638-33c91487-bfa1-42a8-b161-efe4823e4c7c.PNG)
![23](https://user-images.githubusercontent.com/23488019/142552648-104a4faa-38e6-4b50-a79e-4a67d78ef2d6.PNG)


## Results: 

### 1) How is the district summary affected?
On performaing calculations for Thomas High School, it can be noted that there was'nt much difference in the average scores and percentage results for 9th graders. It can be noted that originally there were 39170 students and after removing the THS students the new student count was 38709.

![21](https://user-images.githubusercontent.com/23488019/142551000-164e472f-378e-4cfa-9f62-c63ab97ea3d4.PNG)

![20](https://user-images.githubusercontent.com/23488019/142551005-5480af91-90f3-42e1-bfe5-6c65281390ba.PNG)




![16](https://user-images.githubusercontent.com/23488019/142519551-4e36c80d-4fc8-48ac-bfa5-c2cd1b5c220b.PNG)

### 2) How is the school summary affected?
For Thomas High School, the average math and reading scores were recalculated and school summary updated. It can be noted for Thomas High School that before data cleanup the overall passing percentage was 91%. However after cleanup it went down to 65%. 
![17](https://user-images.githubusercontent.com/23488019/142536233-9807182e-7b51-4bd1-9ef4-638bbb91e57f.PNG)
Before the cleanup, overall percentage is 90%
![16](https://user-images.githubusercontent.com/23488019/142535135-40cb0012-1534-4c08-9143-b26851f10f32.PNG)
After cleanup, overall percentage is 65%.

Hence, there was abig change in Thomas High School's Overall Passing % that moved its rank from 2nd to the 8th after the cleanup. Hence this data analysis could help statistically validate the board member’s suspicion about academic dishonesty at Thomas High School. 

### 3) How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

By replacing Thomas High Schools' ninth graders' math and reading scores, the ranking of the school moved from the 2nd position to the 8th position. Rest of the schools did not see much change in their rankings as much as Thomas High School. Thomas High school was no longer in the list of top 5 schools.

![13](https://user-images.githubusercontent.com/23488019/142515676-2f375373-2b3a-46e6-ad2e-2595ec26ffca.PNG)

### 4) How does replacing the ninth-grade scores affect the following:

For comparative study, we replaced the ninth grade scores. The various aspects of the analysis is discussed below in detail. 

#### - Math and reading scores by grade
We wanted to get more in depth knowledge on the performance of the students at the different schools.Therefore, we tabulated the data according to the grades 9th, 10th, 11th and 12th. This helped us greatly in the comparative study. Math and reading scores for Thomas High School reduced after the cleanup hence supporting the fact that the 9th graders' score were equivalent to failing.

####            Math scores by grade:
- Math Score was set to 'NaN' that is equivalent to 0.
- Student count before the cleanup was 1635.
- Studnet count after the cleanup was 1174. 

![11](https://user-images.githubusercontent.com/23488019/142514962-8a1bba8c-82bc-439e-81a1-e20fbda2c176.PNG)


- Reading Score was set to 'NaN' that is equivalent to 0.
- Student count before the cleanup was 1635.
- Studnet count after the cleanup was 1174. 

![4](https://user-images.githubusercontent.com/23488019/142515194-c6143a8f-9296-4d82-ba0d-1401b28343a6.PNG)

####            Reading scores by grade:

![9](https://user-images.githubusercontent.com/23488019/142515006-01e3c070-f2cd-4dd0-9059-456feab3f6a5.PNG)

![10](https://user-images.githubusercontent.com/23488019/142514996-c488ce85-0bc5-4c69-9acc-9478ef51b0dd.PNG)


 As per the tabulated results we can see that there was hardly any change in the results.
    
#### - Scores by school spending

Various bins were created to analyze the scores based on spending. As per the tabulated results it can be noted that some schools that had the lowest spending per student, still could achieve overall passing percentage of 90%.
    
![7](https://user-images.githubusercontent.com/23488019/142512379-90137ba5-fb41-4f13-8dec-3996f43ea070.PNG)

On the other hand, some other schools with per student spending of over $645 were able to achieve an overall passing percentage of 53% only. Hence the district needs to understand as to how they can support the schools so that they can deliver better results in the future. 

![3](https://user-images.githubusercontent.com/23488019/142510293-c376a1ac-d397-47d9-ae39-ac6b49e44ed2.PNG)


- Thomas High School is in the spending bucket of '$630-644,
- Student count before the cleanup was 1635.
- Studnet count after the cleanup was 1174.


#### - Scores by school size
 
Bins were created and various groups were defined like small, medium and large. The size data was then categorized based on the bins and the results can be seen below.
      
![6](https://user-images.githubusercontent.com/23488019/142511969-9e574e91-49c5-4a53-b813-bdde13126f74.PNG)

![2](https://user-images.githubusercontent.com/23488019/142509868-1c884215-54bd-4eca-abac-e6642df39973.PNG)

#### - Scores by school type

In order to understand which types of schools were performing well, we performed an analysis and found out that the charter schools performed much better than the district schools. The overall percentage for charter schools was found to be 90% as compared to the disctrict schools having just 54%. 

![1](https://user-images.githubusercontent.com/23488019/142509864-5041e684-a16d-4c67-a14c-cbed9c8c146a.PNG)


- Thomas High School is a 'charter' type of school.
- Removing Thomas High School 9th Grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing".

## Summary:

Summarizing the  four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:

 - 1) After nullifying the scores of 9th graders at Thomas High School, there was not much difference in the school district summary.

 - 2) when we nullified the scores of 9th graders at Thomas High school, we could observe that the school lost its rank in the top 5 ranking schools.

 - 3) After revaluation of 10th and 12th scores at Thomas High School, the average scores and percentages changed drastically, resulting in it levelling up.

 - 4) For 10th and 12th grades, after we recalculated the scores, the ranking of Thomas High School moved to the top 5 school rankings in the district. 

 We can also conclude from the overall analysis that the schools excelling academically were mostly charter schools. As a result, the district needs to find various ways to address this issue for the overall improvement in academics.  It was also noted that the schools with more students had a direct impact on their academic success.
