# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

### Overview

The SAT is standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math ([*source*](https://www.princetonreview.com/college/sat-sections)). SAT have different score ranges and each colleges and universities have different score range for their admission ([*source*](https://prepmaven.com/blog/test-prep/average-sat-scores/#:~:text=As%20a%20whole%2C%20the%20average,1564%20for%20total%20SAT%20scores.)). You can read more about on their websites or additional outside sources (a quick Google search will help you understand the scores for [SAT](https://collegereadiness.collegeboard.org/sat) test)

Standardized tests have long been a controversial topic for students, administrators, and legislators. Since the 1940's, an increasing number of colleges have been using scores from sudents' performances on tests like the SAT as a measure for college readiness and aptitude ([*source*](https://www.minotdailynews.com/news/local-news/2017/04/a-brief-history-of-the-sat-and-act/)). Supporters of these tests argue that these scores can be used as an objective measure to determine college admittance. Opponents of these tests claim that these tests are not accurate measures of students potential or ability and serve as an inequitable barrier to entry. 

The digital SAT is a new version of taking SAT test for students. Instead of taking test with pencil and paper, students take the test on the computer ([*source*](https://newsroom.collegeboard.org/sat-program-results-show-increased-participation-class-2022)).

### Problem Statement

The digital SAT will be release in March 2024 for students in the United State. However, the numbers of students who took the SAT test was different from each states and the rate of students who participate in SAT test have changed each year. The purpose of this project is to explore the change of participation rate for the year 2018 and 2019 and identify states that have the SAT participation rate increased.

---

### Datasets

* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))

**Brief description of the contents for each dataset.**

 There are four columns in each dataset:
 
 * First column: name of state that have students participate in SAT test
 
 * Second column: participation rate of students participated in SAT test
 
 * Third column: average evidence-based reading and writing score
 
 * Fourth column: average math score
 
 * Fifth column: total average evidence-based reading and writing score and math score

---

### Outside Research

The school year of 2019 had the highest number of students took the SAT test with more than 2.2 million students participated in the test. The participation rate in 2019 was increase 4% compare to the participation rate of 2018 ([*source*](https://newsroom.collegeboard.org/over-22-million-students-class-2019-took-sat-largest-group-ever)).

---

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT_2018 and SAT_2019|List of state that participate in SAT test| 
|participation|object|SAT_2018 and SAT_2019|Percentage of students participated in SAT test|
|evidence_based_reading_writing|integer|SAT_2018 and SAT_2019|Average evidence based reading writing score|
|math|integer|SAT_2018 and SAT_2019|Average math score|
|total|integer|SAT_2018 and SAT_2019|Total average of evidence based reading writing and math score|
|particapation_rate|float|SAT_2018 and SAT_2019| Convert the percentage of student participated in SAT test to decimal (unit percent divided by 100)| 

---
### Conclusion

* The participation rate of SAT test was increased almost 4% from 2018 to 2019.
* From 2018 to 2019, 23 states that had the SAT test participation rate increase.
* West Virginia was the state that have highest increment rate. The participation rate of West Virginia was increased 71% from 2018 to 2019 (28% in 2018 and 99% in 2019). 
* Following by West Virginia, Florida had the participation rate increase from 56% (in 2018) to 100% (in 2019) which is 44% of increment rate. 
* South Carolina and Oklahoma also have the SAT test participation rate increase above 10%.

---
### Presentation Slide
https://docs.google.com/presentation/d/1Y9C6VCRVFojSwMlNVlLHdb8qOoeHyQ1_LdKTx8HC5T0/edit?usp=sharing
