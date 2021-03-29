# School_District_Analysis

## PURPOSE:
The purpose of this analysis is to analyze data of high schools and its students to provide insights to the School District Board on the merits and spending of each school so the board can make informed decisions and plan ahead.

## RESULTS

### Analysis 1

Raw data:
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

Before:

![district_summary](https://user-images.githubusercontent.com/74985818/112769317-625a3700-8fee-11eb-8f03-dc69971d753d.png)

After:

![district_summary_2](https://user-images.githubusercontent.com/74985818/112769436-ee6c5e80-8fee-11eb-97db-b53e33b278ac.png)

At a high level, district level metrics after excluding the 9th grade for Thomas High School remain unaffected. The only noticable difference is that the average score for Math is reduced by 0.1% and all other metrics remain the same.

### Part 2 - School Summary

Before:

![school_summary](https://user-images.githubusercontent.com/74985818/112770193-88360a80-8ff3-11eb-9632-8c9d23b21403.png)

After:

<img src="https://user-images.githubusercontent.com/74985818/112770378-8b7dc600-8ff4-11eb-94a2-d8051f926827.png" width="800">

As per the highlighted fields above, there's a slight variance in the scoring for Thomas High School. 


### Part 3 - Relative to other schools

Before (Top 5 Schools):

![Top5_1](https://user-images.githubusercontent.com/74985818/112772307-08616d80-8ffe-11eb-8dd1-2a242ca31d72.png)

After (Top 5 Schools):

![Top5_2](https://user-images.githubusercontent.com/74985818/112772321-1911e380-8ffe-11eb-8862-db83ed5ace4c.png)

Though there is change to the performance of students in Thomas High School, the overall performance still has this school as Top 2nd school in the district.

No change to data from earlier analysis.

### Part 4 - Spending Summary

Before:

![spending](https://user-images.githubusercontent.com/74985818/112769078-2a062900-8fed-11eb-953e-31e8195176c9.png)

After:

![spending_2](https://user-images.githubusercontent.com/74985818/112769701-60917300-8ff0-11eb-9798-f3a6f9c81504.png)

No change to data from earlier analysis.

### Part 5 - School Size Summary

Before:

![size](https://user-images.githubusercontent.com/74985818/112771766-7f493700-8ffb-11eb-87be-c8c13d6af1a7.png)

After:

![size_2](https://user-images.githubusercontent.com/74985818/112771090-12806d80-8ff8-11eb-8fa1-ea59775428f8.png)

No change to data from earlier analysis.

### Part 6 - School Type Summary

Before:

![type](https://user-images.githubusercontent.com/74985818/112771983-5ffed980-8ffc-11eb-9cd1-e3680134ea62.png)

After:

![type_2](https://user-images.githubusercontent.com/74985818/112771985-63926080-8ffc-11eb-9f03-1f8cf3640d40.png)

No change to data from earlier analysis.

## Summary
1.The average math exam score for the district was one-tenth of a percentage point lower.
2.The percentage of students who passed the math exam was lowered by two-tenths of a percentage point.
3.The percentage of students who passed the reading exam was lowered by three-tenths of a percentage point.
4.The percentage of students who passed both the math and reading exams for the districts was lowered by one-tenth of a percentage point.



