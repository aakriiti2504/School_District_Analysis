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
### Deliverable 1:
![22](https://user-images.githubusercontent.com/23488019/142552638-33c91487-bfa1-42a8-b161-efe4823e4c7c.PNG)
![23](https://user-images.githubusercontent.com/23488019/142552648-104a4faa-38e6-4b50-a79e-4a67d78ef2d6.PNG)

### Deliverable 2:
![24](https://user-images.githubusercontent.com/23488019/142558584-5dfa9fc3-946e-4874-abf6-949ece5cb1b4.PNG)
![25](https://user-images.githubusercontent.com/23488019/142558570-ac695a27-5649-4d8f-bb8d-4379e1a8c934.PNG)
![26](https://user-images.githubusercontent.com/23488019/142558565-6797e11c-7f3e-4ced-9963-b6cb12c0ed4c.PNG)

#### School District Analysis
- The top 5 and bottom 5 performing schools, based on the overall passing rate
![27](https://user-images.githubusercontent.com/23488019/142558970-54483408-adb4-4ea1-82b5-7abb5b5f8f0e.PNG)
![28](https://user-images.githubusercontent.com/23488019/142558978-d440b4c5-758a-4b63-8c81-4648c3910653.PNG)

- The average math score for each grade level from each school

![37](https://user-images.githubusercontent.com/23488019/142559951-08e3d6a8-30a6-4255-aa89-756f910cb72e.PNG)

- The average reading score for each grade level from each school

![36](https://user-images.githubusercontent.com/23488019/142559954-25bc72f7-50c6-4d17-94ce-f2662f74a828.PNG)


- The scores by school spending per student, by school size, and by school type
#### By Spending
![29](https://user-images.githubusercontent.com/23488019/142559421-11d08b03-4498-4ca0-98f5-e4efafac0980.PNG)

![30](https://user-images.githubusercontent.com/23488019/142559394-1a381f27-9357-43d3-b6e5-ccf1575f4f29.PNG)
![31](https://user-images.githubusercontent.com/23488019/142559385-827af8d1-f4e8-4806-8315-41055b19e786.PNG)

#### By school size
![32](https://user-images.githubusercontent.com/23488019/142559697-77e8c6cb-4a95-46bf-9664-06df05e67a16.PNG)
![33](https://user-images.githubusercontent.com/23488019/142559703-85b9c7aa-3068-4afb-8332-4626ab8517bb.PNG)


#### By school type
![34](https://user-images.githubusercontent.com/23488019/142559795-3da544fc-9a02-440e-9e5d-dacc4ece6fc5.PNG)
![35](https://user-images.githubusercontent.com/23488019/142559799-47735f45-9d4f-4d39-ab89-7107451db307.PNG)


## Results: 

### 1) How is the district summary affected?
On performaing calculations for Thomas High School, it can be noted that there was'nt much difference in the average scores and percentage results for 9th graders. It can be noted that originally there were 39170 students and after removing the THS students the new student count was 38709.

![21](https://user-images.githubusercontent.com/23488019/142551000-164e472f-378e-4cfa-9f62-c63ab97ea3d4.PNG)

![20](https://user-images.githubusercontent.com/23488019/142551005-5480af91-90f3-42e1-bfe5-6c65281390ba.PNG)
 The passing math percentage score also changed from 74.8 to 75%. Passing reading percentage changed from 85.7 to 86%. The overall passing percentage changed from 64.9 to 65%. Hence there was not a lot of major changes.


### 2) How is the school summary affected?
For Thomas High School, the average math and reading scores were recalculated and school summary updated. It can be noted for Thomas High School that before data cleanup the overall passing percentage was 65% and after deliverable 2 it moved up to 90%. 

![40](https://user-images.githubusercontent.com/23488019/142584840-85d00ae3-165e-4cef-9404-a3c29772d350.PNG)

Before and after the cleanup, the overall percentage is 65% and 90%. There was achange in the %passing math, %Passing Reading and %Overall passing where all the values were over 90%.


![41](https://user-images.githubusercontent.com/23488019/142584835-eb03fe39-0387-4312-b7a6-8d402a11d5e5.PNG)



### 3) How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?

By replacing Thomas High Schools' ninth graders' math and reading scores, Rest of the schools did not see much change in their rankings as much as Thomas High School. Thomas High school's initial overall percentage was 65% and then it changed to 90%.

![13](https://user-images.githubusercontent.com/23488019/142515676-2f375373-2b3a-46e6-ad2e-2595ec26ffca.PNG)

### 4) How does replacing the ninth-grade scores affect the following:

For comparative study, we replaced the ninth grade scores. The various aspects of the analysis is discussed below in detail. 

#### - Math and reading scores by grade
We wanted to get more in depth knowledge on the performance of the students at the different schools.Therefore, we tabulated the data according to the grades 9th, 10th, 11th and 12th. This helped us greatly in the comparative study. Math and reading scores for Thomas High School reduced after the cleanup hence supporting the fact that the 9th graders' score were equivalent to negligible. The average math and reading scores for 10th,11th and 12th grades did not change much after the analysis.

####            Math scores by grade:
- Math Score was set to 'NaN' that is equivalent to 0.
- Student count before the cleanup was 1635.
- Studet count after the cleanup was 1174. 

![39](https://user-images.githubusercontent.com/23488019/142582457-5f6fe89a-c08d-4030-91bf-0423e8faab41.PNG)


####            Reading scores by grade:
- Reading Score was set to 'NaN' that is equivalent to 0.
- Student count before the cleanup was 1635.
- Studnet count after the cleanup was 1174. 

![38](https://user-images.githubusercontent.com/23488019/142582468-a5599709-d3af-4060-aac7-258d32511a66.PNG)

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
- Removing Thomas High School 9th Grade scores reduces the "% Passing Math" by 0.1%, "% Passing Reading" by 0.3% and "% Overall Passing" by over 0.3%.

## Summary:

Summarizing the  four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:

 - 1) After nullifying the scores of 9th graders at Thomas High School, there was not much difference in the school district summary.

 - 2) when we nullified the scores of 9th graders at Thomas High school, we could observe that the school lost its rank in the top 5 ranking schools.

 - 3) After revaluation of 10th and 12th scores at Thomas High School, the average scores and percentages changed drastically, resulting in it levelling up.

 - 4) For 10th and 12th grades, after we recalculated the scores, the ranking of Thomas High School moved to the top 5 school rankings in the district. 

 We can also conclude from the overall analysis that the schools excelling academically were mostly charter schools. As a result, the district needs to find various ways to address this issue for the overall improvement in academics.  It was also noted that the schools with more students had a direct impact on their academic success.
