# PyCity Schools Analysis

### Overview of Analysis
Maria, Chief Data Scientist for a local school district believes there has been evidence of academic dishonesty within the school district.  Maria has enlisted my help to analyze math and reading score data and look at what the results are with and without the data they believe to be skewed.  Maria has requested that I create a program that drops the reading and math scores of the students in 9th grade at Thomas High School and provide an analysis.  

### School District Analysis Results:
# The school district data was not largely affected by removing the math and reading scores for the 9th grad students at Thomas High School-- only a marginal drop in scores were seen.
	#Original testing data
	- Average Math Score : 79.0%
	- Average Reading Score : 81.9%
	- Percentage Passing Math : 75.0%
	- Percentage Passing Reading : 85.8%
	- Percentage Overall Passing : 65.2%

	#New testing data
	- Average Math Score : 78.9%
	- Average Reading Score : 81.9%
	- Percentage Passing Math : 78.4%
	- Percentage Passing Reading : 85.7%
	- Percentage Overall Passing : 64.9%

- It does not appear that removing the 9th grader math and reading data caused any affect when rating Thomas High School's performance relative to other schools in the district.  

# WHAT WAS THE IMPACT of NaN?
- When looking at how each grade level was affected by removing the 9th grade math and reading scores from Thomas High School, I think it's safe to say that grades 10-12 were not affected by the removal greatly and the schools other that Thomas High School were not affected in grades 10-12 at all.  The other 9th grades were affected because the null values changed the overall numbers, but it did not provide a great impact.
- Scores by school spending saw each category increase from the original to new by less than 2%, with the Overall Passing increasing in original data from 63% to 66%-- again, only a marginal increase.
- Looking only at the Medium size group (1000-2000) that contains the Thomas High School 9th grade students-- all scores stayed the same in the original and new data!
- A trend that would continue as we evaluate the scores by School Type, no changes for the Charter Schools data.  


## Summary of School District Analysis:  
### NO CHANGES in that data;
is indicative of no academic dishonesty.  The following changes were made: the district average math score dropped from 79.0% to 78.9% once the 9th grade math data from Thomas High School was removed.  The district average reading score did not drop, but actually increased 0.1 from 83.8% to 83.9%.  Both the Percentage Passing Math and Percentage Passing Reading data points dropped by less than an percentage point, making the analysis negligible.  While it could be viewed that the data shows no academic dishonesty, Maria must be vigiliant as she continues to watch the school district- for the 9th grade population at Thomas High School only encompasses a very small fraction of the student population being evaluated.  All parameters should be considered when reviewing and analyzing data.