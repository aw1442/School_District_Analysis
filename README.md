# School_District_Analysis

## Overview of the school district analysis

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the math and reading scores have been replaced, Maria has asked to repeat the school district analysis and write up a report to describe how these changes affected the overall analysis.

## Results

* How is the district summary affected?

![District Summary DF](https://user-images.githubusercontent.com/76754655/111076402-90099100-84c2-11eb-8b2b-2e957cbcd688.PNG)

  * The district summary is affected by the average math score dropping 0.1 and the average reading score, the percentage of passing math, the percentage of reading, and the overall passing percent staying the same based on assessing average scores and passing percentages among the 15 high schools in the school district.
* How is the school summary affected?

![School Summary](https://user-images.githubusercontent.com/76754655/111076625-6f8e0680-84c3-11eb-9d56-46eff77dd481.PNG)

  * After replacing both math and reading scores, Thomas High School's average math score dropped 0.06, average reading core gained 0.05, passing math percentage gained 0.09%, passing reading percentage dropped 0.29%, and overall passing percntage dropped 0.31%, with the same number 2 ranking. 
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![Top 5 Schools updated](https://user-images.githubusercontent.com/76754655/111076657-96e4d380-84c3-11eb-9b0d-d38984031e7f.PNG)

![Bottom 5 Schools updated](https://user-images.githubusercontent.com/76754655/111076692-bc71dd00-84c3-11eb-8415-ace733f8cdb2.PNG)

* After replacing both math and reading scores, Thomas High School maintains the same number 2 ranking relative to other schools. 
* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade

![Math Scores By Grade](https://user-images.githubusercontent.com/76754655/111077955-98b19580-84c9-11eb-85f9-f47d052c9ffa.PNG)

![Reading Scores By Grade](https://user-images.githubusercontent.com/76754655/111077960-9b13ef80-84c9-11eb-9361-c81c145b2d17.PNG)

  * The data replacement did not change the math and reading scores by grade given that the math and reading scores were separated by school and grade level. Thomas High School has "nan" listed for the ninth grade and the remaining data stayed the same.
  * Scores by school spending

![School Spending Summary](https://user-images.githubusercontent.com/76754655/111078040-0fe72980-84ca-11eb-95e7-5f261200ec9d.PNG)

  * When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading scores. However, this data change did impact the spending ranges for passing percentages. According to the summary above, there was a 6% decrease in % passing math, a 7% decrease in % passing reading, and a 7% decrease in % overall passing in the $630-644 spending range.
  * Scores by school size

![Schools By Size](https://user-images.githubusercontent.com/76754655/111078049-15447400-84ca-11eb-8cb4-6134de5d3061.PNG)

  * When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped 6% each. Before the data change, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small (90% overall passing) and large schools (58% overall passing). Given the data change, medium size school are the second in performance (85% overall passing).
  * Scores by school type

![School Type](https://user-images.githubusercontent.com/76754655/111078051-1a092800-84ca-11eb-8fa4-3c8e5aeaf639.PNG)

  * In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.

## Summary

In summary, there are four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:

1. The district summary is affected by the average math score dropping 0.1
2. Thomas High School's average math score dropped 0.06, average reading core gained 0.05, passing math percentage gained 0.09%, passing reading percentage dropped 0.29%, and overall passing percntage dropped 0.31%, with the same number 2 ranking
3. There was a 6% decrease in % passing math, a 7% decrease in % passing reading, and a 7% decrease in % overall passing in the $630-644 spending range
4. For medium-sized schools (1,000-2,000), the % passing math, % passing reading, and % overall passing dropped 6% each
