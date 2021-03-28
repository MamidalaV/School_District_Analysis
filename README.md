# School_District_Analysis

## PURPOSE:
The purpose of this analysis is to analyze data of high schools and its students to provide insights to the School District Board on the merits and spending of each school so the board can make informed decisions and plan ahead.

## RESULTS
### Analysis 1

- List of schools:
![School_List](https://user-images.githubusercontent.com/74985818/112768336-abf45300-8fe9-11eb-9ad5-82497d340be7.png)

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
![school_summary](https://user-images.githubusercontent.com/74985818/112768366-d34b2000-8fe9-11eb-8ad5-5e186de9e69f.png)

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

### Part 4 - School Type Summary
- The merged DataFrame is also sliced to get the following data to create a new dataframe for **Type Summary** based on type:
  1. Average Math Score
  2. Avearge Reading Score
  3. % of students passing Math
  4. % of students passing Reading
  5. Overall Passing %
![type](https://user-images.githubusercontent.com/74985818/112768633-e0b4da00-8fea-11eb-98c3-2e0596b4d1c6.png)

