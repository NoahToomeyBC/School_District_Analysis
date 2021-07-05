# School_District_Analysis
Analyzing standardized testing data using Pandas and Jupyter 
## Overview of Project

### Purpose

In this analysis, we were tasked with finding metrics for a school district's performance based on a number of factors. We were able to sort our data by grade, school, and spending through the use of the pandas dependency for python. We were able to break down the data further to look at one school, Thomas High School, that was having trouble with suspected cheating and were able to remove the potential bad data that could have skewed the analysis.

##### Election Results List
- How is the district summary affected?
 
  - By removing the 9th grade scores from Thomas High School from the overall data, we see a .9% decrease in the overall passing percentage, a .1 point drop in the average math score, a .2% drop in the percentage of students passing math, and a .3% drop in the percentage of students passing reading. The rest of the data remains unaffected.
### Original District Summary
<p align="center">
<img width="1078" height="105" src="https://user-images.githubusercontent.com/85508764/124506843-1d366580-dd92-11eb-9247-124cd8f78274.png">
</p>

### Updated District Summary
<p align="center">
<img width="933" height="54" src="https://user-images.githubusercontent.com/85508764/124506912-435c0580-dd92-11eb-98de-5aee71712746.png">
</p>

- How is the school summary affected?
  - After removing the bad data from Thomas High School, we found that Thomas High School is still the second highest perfroming school overall in the district. It should be kept in mind that the true 9th grade scores could potentially have brought down Thomas High School. More data is required.

### Original School Summary
<p align="center">
<img width="1130" height="628" src="https://user-images.githubusercontent.com/85508764/124506947-566ed580-dd92-11eb-8bbd-7b0337799963.png">
</p>

### Updated School Summary
<p align="center">
<img width="1098" height="628" src="https://user-images.githubusercontent.com/85508764/124506973-61296a80-dd92-11eb-9689-8d0209cf19d2.png">
</p>

  
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade- The math and reading scores are unaffected except for the null value in 9th grade for Thomas High School.
 
 - Scores by school spending - For schools with per student spending between $630 and $644 math averages went down by .01 points, reading averages went up by .01 points, the passing math percentage went down by .02%, the passing reading percentage went up by .02%, and the overall passing went down by .08%.
 
 - Scores by school size - For medium sized schools math averages went down by .01 points, reading averages went up by .01 points, the passing math percentage went down by .01%, the passing reading percentage went up by .06%, and the overall passing went down by .07%.
 
 - Scores by school type - For charter schools math averages went down by .05 points, reading averages went up by .01 points, the passing math percentage went up by .01%, the 
passing reading percentage down by .03%, and the overall passing went down by .04%.

### School District Analysis Summary

While the changes might seem small on paper, with so many students, small percentages can indicate large changes in how we percieve the data. Overall, math averages went down, reading averages went up, passing math percentages were went a full .02% down. Passing reading percentages went down by .03% and the overall percentage went down by almost a full percent. I believe this data shows enough variance that this analysis needs to be re-examined after the ninth graders of Thomas High School have been either given a re-test or further investigation into the academic dishonesty has been performed.

