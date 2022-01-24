# School_District_Analysis

## Overview
A Chief Data Scientist for a city school district has asked for help to analyze data on student funding and students' standardized test scores. Our role in this project is to aggregate the data and showcase trends in school performance. This analysis will aid the city School Board and Superintendent on making decisions regarding the school budget and what to prioritize.
After providing our first analysis, we are informed that there is evidence of academic dishonesty within the reading and math grades for Thomas High School's ninth grade class. This leads us to replace the math and reading scores for Thomas High School's ninth grade class with "NaN's" while keeping the rest of the data intact.

We are provided with two main datasets:
1. students_complete.csv
2. schools_complete.csv

The students_complete.csv has every student sorted by name and School ID along with which school they attend, their gender, grade, and their reading and math scores.
The schools_complete.csv has each school sorted by School ID and contains information on the size of each school and their budgets.

## Results

* How the district summary is affected:
### District - Original Results
![District_Original](https://user-images.githubusercontent.com/95504135/150718621-b35ecc4e-c4a8-4148-a4ed-55909dd78201.png)
### District - Updated Results
![District_Updated](https://user-images.githubusercontent.com/95504135/150718629-2ffe665b-978d-4b2f-b128-5d42756d5d7e.png)

Comparing the original and updated analyses, we can see that the average math score decreased by only 0.1% from 79% to 78.9%, the percentage of passing math decreased by 0.2% from 75% to 74.8%.
The average reading score was not affected but the percentage of passing reading decreased by 0.03% from 86% to 85.7% and the percentage of overall passing decreased by 0.1% from 65% to 64.9%.

* How the school summary is affected:
#### Thomas High School - Original Results
![TH_Original](https://user-images.githubusercontent.com/95504135/150717924-deeb029d-6263-4c10-aa41-d66a8fb102d3.png)
#### Thomas High School - Updated Results
![TH_Updated](https://user-images.githubusercontent.com/95504135/150717927-c77747e4-a076-4b10-8081-7fc2b92224ac.png)

In the original analysis, Thomas High School's overall passing grade was 91% but once the 9th graders' math and reading scores were replaced with "NaN", the updated results for Thomas High School dropped to 65%.

* How replacing the ninth graders' scores affect Thomas High School's performance relative to other schools:
### Thomas High School Performance - Original Results
<img width="988" alt="Performance_Original" src="https://user-images.githubusercontent.com/95504135/150720946-a802193b-0e0b-484c-a925-c60dd6626f03.png">
### Thomas High School Performance - Updated Results
![Performance_Updated](https://user-images.githubusercontent.com/95504135/150720964-98d7b027-9202-4d41-8926-8bfcded2c11f.png)


### Affect of replacing the ninth-grade scores on...:

* Math and reading scores by grade
Thomas High School's 9th graders' original math and reading scores have been replaced with "NaN"

* Scores by school spending
Replacing the ninth-grade scores did not affect Scores by School Spending 

* Scores by school size
Replacing the ninth-grade scores did not affect Scores by School Size

* Scores by school type
Replacing the ninth-grade scores did not affect Scores by School Type

## Summary
