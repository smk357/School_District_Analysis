# School_District_Analysis

### An Analysis of School District Performance

## Overview

The purpose of this project was to assess the impact of changes in the data to school performance results. Specifically, the exclusion of a portion of the dataset (9th grade results Thomas High School) and its imact on school performance metrics.

Reading and math scores for all 9th Grade students of Thomas High School were replace by "NaN" and an analysis was subsequently carried out to determine the following performance metrics: average reading and math score, percentage of students passing math, reading, and both, and outcomes by school budget, school type, and school size.

## Results

### Disctrict summary

The following is a table of the district summary prior to exclusion of the Thomas High School 9th grade scores:

![image](https://user-images.githubusercontent.com/79061124/117589956-0b6e7400-b0fb-11eb-889c-64249c386587.png)

The following is the same table after data removal:

![image](https://user-images.githubusercontent.com/79061124/117589985-4b355b80-b0fb-11eb-8b70-64c9e02d8ee1.png)

- The results indicate a small reduction in average math score, percentage of students passing math, reading, and overall passing percentage - between .1%-.3%. 
- We can conclude that school performace at the district level was not impacted in a statistically significant way by removing a portion of the data.

### School Summary

The following is a table of the school summary prior to exclusion of the Thomas High School 9th grade scores:

![image](https://user-images.githubusercontent.com/79061124/117590245-779da780-b0fc-11eb-8993-4a702552a1e9.png)

The following is the same table after data removal:

![image](https://user-images.githubusercontent.com/79061124/117590296-c3505100-b0fc-11eb-8bd9-2cfc0cc88e31.png)

- The tables are identical except for the results for Thomas High School. 
- As the number of students used to calculate percentage passing rates was not updated to exclude 9th grade students in this table, the results show compartively poor performance metrics, however this is not a true representation of the performance of grade 10-12 students at Thomas High School.

### Thomas High School

The following is a table of the performance results for Thomas High School after 9th grade scores were replaced:

![image](https://user-images.githubusercontent.com/79061124/117590629-69e92180-b0fe-11eb-92bb-d8db25b3bf8b.png)

- Thre results demonstrate a significant imporvement in Thomas High School's performance from the previous table after replacing the 9th grade scores. This is mainly a result of a lower number of students after the 9th grade results were replaced
- Average math and reading scores are between 83%-84% and passing rates for math, reading, and both are between 90%-97%. 
- The data indicates strong performance from grade 10-12 students compared to other schools - Thomas High School is within the top 5 best performing schools:

![image](https://user-images.githubusercontent.com/79061124/117590829-3f4b9880-b0ff-11eb-94f3-636271778d0f.png)


### Math and Reading Scores by Grade

#### Math
![image](https://user-images.githubusercontent.com/79061124/117591002-1b3c8700-b100-11eb-98b3-9d6992d1b735.png)


#### Reading

![image](https://user-images.githubusercontent.com/79061124/117591020-43c48100-b100-11eb-89c7-88b181328c67.png)

- The results are indentical to the tables prior to removing 9th grade Thomas High School Results, excepts for the results for Thomas High School
- 9th grade results for Thomas are replaced by "NaN"

### Scores by School Spending

Bofore replacing

![image](https://user-images.githubusercontent.com/79061124/117591271-bc780d00-b101-11eb-80cd-276a92f69196.png)

After replacing

![image](https://user-images.githubusercontent.com/79061124/117591281-d31e6400-b101-11eb-873f-006da393f6ec.png)

- Identical results

### Scores by School Size

Before replacing

![image](https://user-images.githubusercontent.com/79061124/117591338-14af0f00-b102-11eb-8ab6-2d700904089d.png)

After replacing

![image](https://user-images.githubusercontent.com/79061124/117591371-2b556600-b102-11eb-9fef-491612ac5c44.png)

- Identical results

### Scores by School Type

Before replacing

![image](https://user-images.githubusercontent.com/79061124/117591413-5b9d0480-b102-11eb-89a4-fa13c9b02213.png)

After replacing

![image](https://user-images.githubusercontent.com/79061124/117591427-75d6e280-b102-11eb-91da-5a681fae2312.png)

- Identical results

## Summary

- The results mainly affected scores for Thomas High School, with statistically insignificant changes to overall performance based on shool size, budget, and type, due to replacing the Thomas 9th grade scores
- Thomas High School remained in the top 5 performers despite removing data for an entire grade
- There was no impact on the higher performance of Charter schools
- The altered 9th grade results were too small a subsample to have any statistically significant effects on overall performance metrics
