## School_District_Analysis.

#Overview of the school district analysis:

We have nalyzed the standardized test results of two subjects for fifteen schools in our school district. We have taken into consideration the type of school, the size of the school, and the budget per student of the schools. Our goal is to discern how perfermance is affected by the the budget, the size of the school, and whether charter schools are delivering their promises. A priority in our investigation is an allegation of academic dishonesty

#Results:

How is the district summary affected?
  -Average math score has dropped 0.1 pts
  -Average reading score is statistically unaffected
  -Percent passing math has declined by 0.2%
  -Percent passing reading is down 0.3%
  -Percent overall passing is slightly diminished by 0.1%
How is the school summary affected?
  -Thomas High School:
     -Average math score down <0.1 point (negligible)
     -Average reading score up <0.1 point (negligible)
     -Percent passing math down 0.1%
     -Percent passing reading down 0.3%
     -Overall passing percent down 0.3%
  
  
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  -Thomas High School was unaffected in its relative performance to other schools. THS is still the second-highest performing school overall.

How does replacing the ninth-grade scores affect the following:
  Math and reading scores by grade
    -THS has no 9th grade math and reading scores. Fortunately, no other schools or grades are affected.

  Scores by school spending
    -Second highest bracket was not not affected in average scores or percent passing either subject or overall passing.

  Scores by school size
    -Thomas High School is in the medium-sized tier, which was not affected by replacing 9th-grade scores.

  Scores by school type
    -Thomas High School, a charter school, did not contribute to a statistically significant change in charter schools when their 9th grade scores were replaced.    

#Summary:

It is notable to point out that when 9th grade scores were replaced with NaN results, the percent passing math, reading, and overall dropped significantly. This can be explained by considering that the numerator in scores/total students decreased without modifying total students. Once the grade was removed altogether from the dataset, our figures resumed normalcy. This is a good indicator that widespread fraud is unlikely to be pervasive.
