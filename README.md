# School District Analysis 

Overview of the Analysis

Purpose: The purpose of this analysis is to assist school board superintendents in making school and district level decisions about school's budgets and priorities. I will assist Maria, the Chief Data Scientist for a City School District, in aggregating and analyzing data on student funding and student's standardized test scores as well as showcasing trends on school performance. 

During this analysis, Maria asked me to replace the ninth graders' math and reading scores for Thomas High School with NaNs (an undefined number) due to evidence of academic dishonesty. 

Task Deliverables: The goal of this analysis is to examine how replacing the ninth graders' math and reading scores affected the School District Analysis.

The School District Analysis includes:
- a district summary
- a school summary
- the top 5 and bottom 5 performing schools
- the average math score for each grade level from each school
- the average reading score for each grade level from each school
- the scores by school spending per student, by school size, and by school type. 


Results: 

How is the district summary affected?

Original District Summary: 

![district summary](https://user-images.githubusercontent.com/86159728/135667403-c526e115-18dd-4da4-8825-9e2f5accb3a5.jpg)

Updated District Summary: 
![updated district summary](https://user-images.githubusercontent.com/86159728/135667239-d55ed043-8254-49a4-a586-ac705157184d.jpg)

- In the updated district summary the average math score, % passing math, % passing reading, and % overall passing is slightly lower than the original district summary
- The average reading score is the same 

How is the school summary affected? How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Original School Summary:

![school summary](https://user-images.githubusercontent.com/86159728/135668244-d8c5aa28-545b-4f73-89d5-99abdc97e352.jpg)

Updated  School Summary:

![updated summary by school](https://user-images.githubusercontent.com/86159728/135696499-22d70df2-0505-43e1-96b4-dedfaf035fb4.jpg)

- The school summary is the same between the updated and original per school summary dataframe, except for Thomas High School. 
- For Thomas High School, the average math score is lower (83.350937 versus 83.418349), the average reading score is higher (83.896082 versus 83.848930), the % passing math is lower (93.185690 versus 93.272171), the % passing reading is lower (97.018739 versus 97.308869), and the % overall passing is lower (90.630324 versus 90.948012).

How are the top 5 and bottom 5 schools affected?

Original Top 5 and Bottom 5 Schools:

![top and bottom schools](https://user-images.githubusercontent.com/86159728/135668694-c29fa268-13c8-45c4-b6ca-2dffbf0dadf4.jpg)

Updated Top 5 and Bottom 5 Schools:

![updated top and bottom schools](https://user-images.githubusercontent.com/86159728/135668787-c15cfc6e-59d7-4403-a15d-5b450b36e53d.jpg)

- Top 5 and bottom 5 schools are in the same order
- Although the average scores and % passing values changed for Thomas High School, it is still ranked at second position in the top 5.

How are math and reading scores by grade affected?

Original Math Scores by Grade:

![math average by grade](https://user-images.githubusercontent.com/86159728/135669210-cf447136-3e81-48f2-8541-dd17d044d574.jpg)

Original Reading Scores by Grade: 

![reading scores by grade](https://user-images.githubusercontent.com/86159728/135692944-a5e189f0-1a4a-4c80-8e04-fc6de011b8c1.jpg)

Updated Math Scores by Grade:

![updated math score by grade](https://user-images.githubusercontent.com/86159728/135695926-fbc28219-11ec-42ec-8421-58288ac8c874.jpg)

Updated Reading Scores by Grade:

![updated reading scores by grade](https://user-images.githubusercontent.com/86159728/135692971-19b0abb8-3823-4698-aed2-d2cee56b8cdd.jpg)

- For all schools, except Thomas High School, the average math and reading scores are the same for all grades
- The average math and reading scores remained the same for 10th, 11th, and 12th graders in Thomas High School.
- The 9th grade averages were replaced by NaN values for Thomas High School.

How are scores by school spending, school size, and school type affected?

Original Scores by School Spending:

![scores by student spending](https://user-images.githubusercontent.com/86159728/135669478-04f0d772-a9ff-42a1-bb62-bb92c1428840.jpg)

Updated Scores by School Spending:

![updated scores by spending](https://user-images.githubusercontent.com/86159728/135669500-d548aa20-1d76-4324-af15-1e86195ff41d.jpg)

Original Scores by School Size:

![scores by school size](https://user-images.githubusercontent.com/86159728/135669629-6e64576e-b3a0-4be7-9615-4271b0fda9ac.jpg)

Updated Scores by School Size:

![updated scores by school size](https://user-images.githubusercontent.com/86159728/135669650-ddd42c50-9684-465e-a0b7-def289e2ebed.jpg)

Original Scores by School Type:

![scores by school type](https://user-images.githubusercontent.com/86159728/135669693-a36ed2fd-2ecd-4ef3-ac9d-2094ffec41ab.jpg)

Updated Scores by School Type:

![updated scores by school type](https://user-images.githubusercontent.com/86159728/135669717-b810b36a-716c-4c58-abf7-a15af718f681.jpg)

- The updated average scores by school spending, school size and school type were the same as the original.
- The trend for average scores by school spending is that the lower the spending range, the higher the reading and math scores
- The trend for average scores by school size is that small and medium size schools have higher scores than large schools
- The trend for average scores by school type is that the charter schools have higher scores than district schools

Summary of the main changes between the updated and the original School District Analysis: 
1) The average math score for Thomas High School and the district summary is lower
2) The % passing math for Thomas High School and the district summary is lower
3) The % passing reading for Thomas High School and the district summary is lower
4) The % overall passing for Thomas High School and the district summary is lower
5) Thomas High School Grade 9 scores were replaced with NaN.
