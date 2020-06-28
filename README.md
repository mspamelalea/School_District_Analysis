# School_District_Analysis
Analyzing school district standardized testing data for Maria.
Python code to collect, tabulate, analyze election results. This is an exercise for Module 4 the Data Anaylysis Bootcamp at Vandy.
Complete and election audit/analysis of a recent Colorado local congressional election.
- An big-picture review of the district's key measurements., presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics: 
	o Top 5 and bottom 5 performing schools, based on the overall passing rate (both math and reading scores)
	o The average math score for students in each grade level (9th - 12th) at each school
	o The average reading score for students in each grade level (9th - 12th) at each school
	o Each school's performance based on the budget per student
	o Each school's performance based on the school size 
	o Each school's performance based on the type of school

After providing the analysis to Maria, she determined that all 9th grade scores at Thomas High Schoool were invalid and asked that the 9th grade scores from that school be removed from the analysis.
Once those scores were removed, the same analysis was provided below with the remaining data.

# Resources
Data Source: 
- schools_complete.csv
- students_complete.csv

Software: 
- Pyton 3.7.6 
- Jupyter Notebook 6.0.3
- Pandas 1.0.1
- Numpy 1.18.1

# Summary
Resulting analysis of the district's standardized testing data.
School District Summary after removing invalid scores

How is the district summary affected?

- The average math score dropped by < 1%
- The average reading score was not affected
- The percentage passing math dropped by 1%
- The percentage passing reading dropped by 1%
- The overall passing rate dropped by 1%

How is the school summary affected?

- The Per School summary was only affected for Thomas High School:
-  percentage passing math dropped from 93.2% to 66.9%
-  percentage passing reading dropped from 97.3% to 69.7%
-  overall passing percentage dropped from 90.9% to 65.1%

How were the School rankings affected?

- Thomas High School dropped out of the Top 5 moving Wright High School into the top 5
- The Bottom 5 schools remained the same

How were the other reports affected?

	Math and Reading Scores by Grade remained the same except for Thomas High School which 
    reported had no data to report

	Scores by School Spending changed at the $630-644 range:
    -  percentage passing math dropped from 73% to 67%
    -  percentage passing reading dropped from 84% to 77%
    -  overall passing percentage dropped from 63% to 56%
    
	Scores by School Size changed at the Medium(1000-2000) size:
    -  percentage passing math dropped from 94% to 88%
    -  percentage passing reading dropped from 97% to 91%
    -  overall passing percentage dropped from 91% to 85%
    
	Scores by School Type changed by Charter school type:
    -  percentage passing math dropped from 94% to 90%
    -  percentage passing reading dropped from 97% to 93%
    -  overall passing percentage dropped from 90% to 87%


