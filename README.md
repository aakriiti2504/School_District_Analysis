# School_District_Analysis
This analysis consists of two technical deliverables and written report to present the results on the ninth grade reading and math scores and  perform school district analysis. 


## Background: 

Maria, the chief data scientist for a city school district is responsible for analyzing information from a variety of resources and in a variety of formats. In this role she has a task of preparing all standardized test data for analysis, reportings and presesntation to provide insights about performance trends and patterns. These insights are used for informd discussions and strategic decisions at the school and district level. 

## Overview of the school district analysis (Purpose):

I will be helping Maria analyze data on student funding and students standardized test scores. I am given access to every student's math and reading scores, as well as various information on the schools they attend. My task is to aggregate the data and showcase trends in school performance. This analysis will assist the school board and the superintendent in making decisions regarding the school budget and priorities. For this task, the Family Educational Rights and Privacy Act(FERPA) of 1974 is taken into consideration as it protects the  privacy of student education records. This law applies to all school that receive funds under an applicable program of the US Department of Education. The data is to be treated with utmost confidentiality to protect the students I am reporting on. 

## Tools used:

Maria advises to download and install a software calle Anaconda, a free open source distribution software for over 1500 packages, to perform the analysis. She has also provide some instructions and video tutorials. The analysis of school data will be done using the package 'Jupyter Notebook'.Jupyter Notebook is to Anaconda what Microsoft Word is to Microsoft Office. Anaconda packages support the Python and R programming languages for datatscience, machine learning and data processing and so on. Here we will be using Python too.
Data source - election_results.csv file is an Excel file with given data.
- Software - Python 3.7.8, Visual Studio Code, Anaconda, Jupyter Notebook
- Data Source - PyCitySchools.ipynb
- Libraries - Pandas
- Add,commit,push - GitBash and GitHub

## Results: 

### 1) How is the district summary affected?
### 2) How is the school summary affected?

### 3) How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
By replacing Thomas High Schools' ninth graders' math and reading scores, the ranking of the school moved from 2md place to 8th place.

### 4) How does replacing the ninth-grade scores affect the following:
For comparative study, we replaced the ninth grade scores. The various aspects of the analysis is discussed below in detail. 

#### - Math and reading scores by grade
We wanted to get more in depth knowledge on the performance of the students at the different schools.Therefore, we tabulated the data according to the grades 9th, 10th, 11th and 12th. This helped us greatly in the comparative study.

####            Math scores by grade:

![11](https://user-images.githubusercontent.com/23488019/142514962-8a1bba8c-82bc-439e-81a1-e20fbda2c176.PNG)

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

#### - Scores by school size
 
Bins were created and various groups were defined like small, medium and large. The size data was then categorized based on the bins and the results can be seen below.
      
![6](https://user-images.githubusercontent.com/23488019/142511969-9e574e91-49c5-4a53-b813-bdde13126f74.PNG)

![2](https://user-images.githubusercontent.com/23488019/142509868-1c884215-54bd-4eca-abac-e6642df39973.PNG)

#### - Scores by school type

In order to understand which types of schools were performing well, we performed an analysis and found out that the charter schools performed much better than the district schools. The overall percentage for charter schools was found to be 90% as compared to the disctrict schools having just 54%. 

![1](https://user-images.githubusercontent.com/23488019/142509864-5041e684-a16d-4c67-a14c-cbed9c8c146a.PNG)

## Summary:

Summarizing the  four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:

 - 1) After nullifying the scores of (th graders at Thomas High School, there was not much difference in the school district summary.

 - 2) when we nullified the scores of 9th graders at Thomas High school, we could observe that the school lost its rank in the top 5 ranking schools.

 - 3) After revaluation of 10th and 12th scores at Thomas High School, the average scores and percentages changed drastically, resulting in it levelling up.

 - 4) For 10th and 12th grades, after we recalculated the scores, the ranking of Thomas High School moved to the top 5 school rankings in the district. 

 We can also conclude from the overall analysis that the schools excelling academically were mostly charter schools. As a result, the district needs to find various ways to address this issue for the overall improvement in academics.  It was also noted that the schools with more students had a direct impact on their academic success.
