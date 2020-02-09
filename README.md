# School_District_Analysis
Analyze school district data: standardized testing results, create reports and presentations.

## Overview
A high-level snapshot of the district's key metrics, presented in a table format
	- An overview of the key metrics for each school, presented in a table format
	- Tables presenting each of the following metrics:
	- Top 5 and bottom 5 performing schools, based on the overall passing rate
	- The average math score received by students in each grade level at each school
	- The average reading score received by students in each grade level at each school
	- School performance based on the budget per student
	- School performance based on the school size 
	- School performance based on the type of school
	
## Resources

schools_complete_csv
student_data_csv

Before completing any analysis, cleaned data by creating cleaning_student_names.ipynb

Merged the two dataframes, school_data_df and student_data_df to combine the two files into a single dataset in order to provide a school district summary as a high-level snapshot of the district's key metrics: 
	- Total number of students
	- Total number of schools
	- Total budget
	- Average math score
	- Average reading score
	- Percentage of students who passed math
	- Percentage of students who passed reading
	- Overall passing percentage

Created a District Summary to include:
	- Total number of schools in the column “Total Schools”
	- Total number of students in the column “Total Students”
	- Total budget in the column “Total Budget”
	- Average reading score in the column “Average Reading Score”
	- Average math score in the column “Average Math Score”
	- Percentage of students passing reading in the column “% Passing Reading”
	- Percentage of students passing math in the column “% Passing Math”
	- Overall passing percentage in the column “% Overall Passing”

Got the following key metrics for each school and place them in a School Summary DataFrame. The key metrics: 
	- School name
	- School type
	- Total students
	- Total school budget
	- Per student budget
	- Average math score
	- Average reading score
	- Percent passing math
	- Percent passing reading
	- Percent overall passing

School Summary includes:

	- Type of school in the “School Type” column
	- Total students per school in the “Total Students” column
	- Total budget per school in the “Total School Budget” column
	- Total budget per student for each school in the “Per Student Budget” column
	- Average math score for each school in the “Average Math Score” column
	- Average reading score for each school in the “Average Reading Score” column
	- Percentage of students passing math for each school in the “% Passing Math” column
	- Percentage of students passing reading for each school in the “% Passing Reading” column
	- Overall passing percentage for each school in the “% Overall Passing” column

Displayed the Highest-Performing Schools by percentage of Overall Passing.  The top five are:

Cabrera High School: 91%

Griffin High School: 91%

Pena High School: 91%

Thomas High School: 91%

Wilson High School: 91%


Displayed the Lowest-Performing Schools.  The lowest 5 are:

Figueroa High School: 53%

Rodriguez High School: 53%

Ford High School: 54%

Hernandez High School: 54%

Huang High School: 54%


Added grade-levels to dataframe to display average math and reading scores per grade-level for insight per grade-level.

Created a Spending Summary to display the Spending Ranges Per Student, Average Math Score, Average Reading Score, Percentage of Passing Math, Percentage of Passing Reading and Overall Percentage of passing both math and reading.

Created a Summary based on school size in the ranges of:
Small (<1000)
Medium (1000-2000)
Large (2000-5000)

Created a Summary based on the two types of schools:
Charter
District

