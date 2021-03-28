# School_District_Analysis

## PURPOSE:
The purpose of this analysis is to analyze data of high schools and its students to provide insights to the School District Board on the merits and spending of each school so the board can make informed decisions and plan ahead.

## RESULTS

### Analysis 1

- List of Schools (All data):
![School_List](https://user-images.githubusercontent.com/74985818/112771208-c7b32580-8ff8-11eb-895d-1b47223d162e.png)

- List of students (sample set):
![Student_list](https://user-images.githubusercontent.com/74985818/112768345-b44c8e00-8fe9-11eb-95c1-0611317af165.png)

- The data from these files are merged to create a single dataframe and is used to analyze various data points.
![merged](https://user-images.githubusercontent.com/74985818/112768353-c62e3100-8fe9-11eb-85a2-fabe75bd6d33.png)


### District Summary
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

### School Summary
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

### Spending Summary
- The merged DataFrame is further sliced to get the following data to create a new dataframe for **Spending Summary** based on spending:
  1. Average Math Score
  2. Avearge Reading Score
  3. % of students passing Math
  4. % of students passing Reading
  5. Overall Passing %
![spending](https://user-images.githubusercontent.com/74985818/112768584-a9462d80-8fea-11eb-8d0e-1a886d23d7a8.png)

### School Size Summary
- The schools are bucketed based on their size:
![size](https://user-images.githubusercontent.com/74985818/112768615-cb3fb000-8fea-11eb-98de-6e888f911e3f.png)

### School Type Summary
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

![district_summary](https://user-images.githubusercontent.com/74985818/112769317-625a3700-8fee-11eb-8f03-dc69971d753d.png)
![district_summary_2](https://user-images.githubusercontent.com/74985818/112769436-ee6c5e80-8fee-11eb-97db-b53e33b278ac.png)


### Part 2 - School Summary
![school_summary](https://user-images.githubusercontent.com/74985818/112770193-88360a80-8ff3-11eb-9632-8c9d23b21403.png)
<img src="https://user-images.githubusercontent.com/74985818/112770378-8b7dc600-8ff4-11eb-94a2-d8051f926827.png" width="800">

### Math and Reading Scores by Grade
![math_by_grade](https://user-images.githubusercontent.com/74985818/112769052-1064e180-8fed-11eb-955a-e141497aadeb.png)
![reading_by_grade](https://user-images.githubusercontent.com/74985818/112769055-1490ff00-8fed-11eb-8e26-7823ce76a215.png)

### Part 4 - Spending Summary
![spending](https://user-images.githubusercontent.com/74985818/112769078-2a062900-8fed-11eb-953e-31e8195176c9.png)
![spending_2](https://user-images.githubusercontent.com/74985818/112769701-60917300-8ff0-11eb-9798-f3a6f9c81504.png)

### Part 5 - School Size Summary
![size](https://user-images.githubusercontent.com/74985818/112771089-10b6aa00-8ff8-11eb-91c5-f98872ec16fd.png)
![size_2](https://user-images.githubusercontent.com/74985818/112771090-12806d80-8ff8-11eb-8fa1-ea59775428f8.png)

### Part 6 - School Type Summary

