# School_District_Analysis

## PURPOSE:
The purpose of this analysis is to analyze data of high schools and its students to provide insights to the School District Board on the merits and spending of each school so the board can make informed decisions and plan ahead.

## RESULTS
### Analysis 1

- List of schools (all data):
![School_List](https://user-images.githubusercontent.com/74985818/112768336-abf45300-8fe9-11eb-9ad5-82497d340be7.png)
<img src="https://user-images.githubusercontent.com/74985818/112768336-abf45300-8fe9-11eb-9ad5-82497d340be7.png" width="100" height="100">

- List of students (sample set):
![Student_list](https://user-images.githubusercontent.com/74985818/112768345-b44c8e00-8fe9-11eb-95c1-0611317af165.png)

- The data from these files are merged to create a single dataframe and is used to analyze various data points.
![merged](https://user-images.githubusercontent.com/74985818/112768353-c62e3100-8fe9-11eb-85a2-fabe75bd6d33.png)


### Part 1 - District Summary
- The merged DataFrame is then sliced to get the following data to create a new dataframe for **District Summary**:
  1. Total Schools in the district
  2. Total students in the district
  3. Total budget
  4. Average Math Scores
  5. Average Reading Scores
  6. % of students passing Math
  7. % of students passing Reading
  8. Overall Passing %
![district_summary](https://user-images.githubusercontent.com/74985818/112768360-cd553f00-8fe9-11eb-8b65-88bd4a85e9de.png)

### Part 2 - School Summary
- The merged DataFrame is also sliced to get the following data to create a new dataframe for **School Summary**:
  1. Type of school
  2. Total students per school
  3. Total budget per school
  4. Budget per student
  5. Average Math Scores
  6. Average Reading Scores
  7. % of students passing Math
  8. % of students passing Reading
  9. Overall Passing %

### Part 3 - Spending Summary
- The merged DataFrame is further sliced to get the following data to create a new dataframe for **Spending Summary** based on spending:
  1. Average Math Score
  2. Avearge Reading Score
  3. % of students passing Math
  4. % of students passing Reading
  5. Overall Passing %
![spending](https://user-images.githubusercontent.com/74985818/112768584-a9462d80-8fea-11eb-8d0e-1a886d23d7a8.png)

### Part 4 - School Size Summary
- The schools are bucketed based on their size:
![size](https://user-images.githubusercontent.com/74985818/112768615-cb3fb000-8fea-11eb-98de-6e888f911e3f.png)

### Part 5 - School Type Summary
- The merged DataFrame is also sliced to get the following data to create a new dataframe for **Type Summary** based on type:
  1. Average Math Score
  2. Avearge Reading Score
  3. % of students passing Math
  4. % of students passing Reading
  5. Overall Passing %
![type](https://user-images.githubusercontent.com/74985818/112768633-e0b4da00-8fea-11eb-98c3-2e0596b4d1c6.png)

### Analysis 2
- Due to the evidence of academic dishonesty, Math and Reading scores for 9th Grade students of Thomas High School were disregarded. Results are below:

### Comparision between Analysis 1 and Analysis 2

### Part 1 - District Summary
Analysis 1
![district_summary](https://user-images.githubusercontent.com/74985818/112769317-625a3700-8fee-11eb-8f03-dc69971d753d.png)
![district_summary_2](https://user-images.githubusercontent.com/74985818/112769436-ee6c5e80-8fee-11eb-97db-b53e33b278ac.png)

Analysis 2


### Part 2 - School Summary
Analysis 1
![school_summary](https://user-images.githubusercontent.com/74985818/112768366-d34b2000-8fe9-11eb-8ad5-5e186de9e69f.png)

Analysis 2
![school_summary_2](https://user-images.githubusercontent.com/74985818/112768994-c1b74780-8fec-11eb-8fcb-bff496841b15.png)

### Math and Reading Scores by Grade
![math_by_grade](https://user-images.githubusercontent.com/74985818/112769052-1064e180-8fed-11eb-955a-e141497aadeb.png)
![reading_by_grade](https://user-images.githubusercontent.com/74985818/112769055-1490ff00-8fed-11eb-8e26-7823ce76a215.png)


### Part 4 - Spending Summary
Analysis 1
![spending](https://user-images.githubusercontent.com/74985818/112769078-2a062900-8fed-11eb-953e-31e8195176c9.png)

Analysis 2


### Part 5 - School Size Summary
Analysis 1

Analysis 2

### Part 6 - School Type Summary
Analysis 1

Analysis 2
