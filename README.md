# pandas-challenge
by: Panfilo Marbibi

Files:

pandas-challenge
	- Readme.md
	PyCitySchools
		Resources
			- schools_complete.csv
			- students_complete.csv
	
		-PyCitySchool.ipynb


PyCitySchool.ipynb
	
	Summary:

		This jupyter notebook reads the files, 'school_complete.csv', and 'students_complete.csv', that are in the 'Resources' folder and does an analysis on the data within the csv's. An overall analysis from the data can be found at the top of the notebook. This notebook combines the two files and creates data frames based on the information that is stored.

per_school_summary (Data Frame)

	- groups by school name, and shows the school type, total students, total school budget, per student budget, average math score, average reading score, %passing math, %passing reading, and %overall passing.
	- more specific data frames are made from this data frame.


top_school (Data Frame)
	
	- Sorts the data by the %Overall Passing column by descending order from greatest to least.

bottom_schools (Data Frame)

	- Sorts the data by the %Overall Passing column by ascending order from least to greatest.

math_scores_by_grade (Data Frame)

	- Collects the average math scores for each school and subdividing by grade.

reading_scores_by_grade (Data Frame)

	- Collects the average reading scores for each school and subdividing by grade.

school_spending_df (Data Frame)
	
	-  Copies the data  from per_school_summary  and creates a new column, 'Spending Ranges (Per Student)'

spending_summary (Data Frame)
	
	- groups the findings in school_spending_df and bins together schools by the 'Spending Ranges (Per Student)'


per_school_summary (Data Frame)

	- Creates a new column, 'School Size,' that has groupings of the schools by number of students.

size_summary (Data Frame)

	- Groups together the schools by 'School Size' = Small, Medium, and Large, and shows the average passing rate for math, reading, and overall.

type_summary (Data Frame)

	- Groups together the schools by 'School Type' = Charter or District, and shows the average passing rate for math, reading, and overall.



Disclaimer:
pandas code used in this notebook was derived from activities in class.