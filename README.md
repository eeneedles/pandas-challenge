# pandas-challenge
This is a project analyzing district-wide standardized test results using pandas.  Included in the PyCitySchools folder is a Jupyter Notebook file called PyCitySchools_starter and a Resources folder containing two cvs files with math and reading test scores and budgetary information for the district by school and by student.
PyCitySchools_starter contains calculations and DataFrames with counts and averages for schools, students, budgets, math scores and reading scores.

A DataFrame was created merging two csv files for school data and student data on the common series "School Name".  From the merged DataFrame, a School District summary was completed and a snapshot DataFrame was created from the calculations for number of schools, number of students, total budget for all schools, average math and reading scores for all schools, and percentages for passing reading and math scores.

A second DataFrame was completed for the summary of each school, which included the calculations for number of students, school budget, per capita spending, average test scores, number of passing math and reading scores, number of students who passed both math and reading, and the passing rates for math, reading, and overall passing.

The DataFrame was sorted to show the five highest and lowest performing schools by percentage.  Other DataFrames include the math and reading scores by grade, scores by school budget, and scores by school size and type.  The markdown cell includes an analysis of observable trends in the data.

Source for .nunique function: statology.org/pandas-count-unique-values/
