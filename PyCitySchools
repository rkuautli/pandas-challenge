import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'School Type': ['Public', 'Private', 'Public', 'Private'],
    'Average Math Score': [85, 78, 80, 90],
    'Average Reading Score': [88, 82, 84, 92],
    '% Passing Math': [90, 75, 80, 95],
    '% Passing Reading': [92, 80, 85, 98],
    '% Overall Passing': [85, 70, 75, 93]
}

# Create DataFrame
per_school_summary = pd.DataFrame(data)

# Group by "School Type" and calculate averages for each metric
average_math_score_by_type = per_school_summary.groupby("School Type")["Average Math Score"].mean()
average_reading_score_by_type = per_school_summary.groupby("School Type")["Average Reading Score"].mean()
average_percent_passing_math_by_type = per_school_summary.groupby("School Type")["% Passing Math"].mean()
average_percent_passing_reading_by_type = per_school_summary.groupby("School Type")["% Passing Reading"].mean()
average_percent_overall_passing_by_type = per_school_summary.groupby("School Type")["% Overall Passing"].mean()

# Assemble results into a single DataFrame
type_summary = pd.DataFrame({
    'Average Math Score': average_math_score_by_type,
    'Average Reading Score': average_reading_score_by_type,
    '% Passing Math': average_percent_passing_math_by_type,
    '% Passing Reading': average_percent_passing_reading_by_type,
    '% Overall Passing': average_percent_overall_passing_by_type
})

# Display the type_summary DataFrame
print("Type Summary DataFrame:")
print(type_summary)

Student ID	student_name	gender	grade	school_name	reading_score	math_score	School ID	type	size	budget
0	0	        Paul Bradley	M	      9th	  Huang High School	66	      79	          0	District	2917	1910635
1	1	        Victor Smith	M	      12th	Huang High School	94	      61	          0	District	2917	1910635
2	2	        Kevin Rodriguez	M	    12th	Huang High School	90	      60	          0	District	2917	1910635
3	3	        Dr. Richard Scott	M	  12th	Huang High School	67	      58	          0	District	2917	1910635
4	4	        Bonnie Ray	  F	      9th	Huang High School	  97	      84	          0	District	2917	1910635

# Calculate the total number of unique schools
school_count =
school_count
import pandas as pd

# school_data = pd.read_csv('path_to_your_csv_file.csv')

# Calculate the total number of unique schools
total_schools = school_data['school_name'].nunique()

print(f'Total number of unique schools: {total_schools}')
15

# Calculate the total number of students
student_count =
student_count
import pandas as pd

# Assuming you have loaded your data into a DataFrame named school_data
# For example:
# school_data = pd.read_csv('path_to_your_csv_file.csv')

# Calculate the total number of students
total_students = school_data['size'].sum()

print(f'Total number of students: {total_students}')
39170

# Calculate the total budget
total_budget =
total_budget
import pandas as pd

# Assuming you have loaded your data into a DataFrame named school_data
# For example:
# school_data = pd.read_csv('path_to_your_csv_file.csv')

# Calculate the total budget
total_budget = school_data['budget'].sum()

print(f'Total budget for all schools: ${total_budget:,}')  # Using : for comma separator in thousands
24649428

# Calculate the average (mean) math score
average_math_score =
average_math_score
import pandas as pd

# student_data = pd.read_csv('path_to_your_csv_file.csv')

# Calculate the average math score
average_math_score = student_data['math_score'].mean()

print(f'Average math score: {average_math_score:.2f}')  # Print with two decimal places
78.985

# Calculate the average (mean) reading score
average_reading_score =
average_reading_score
import pandas as pd

# student_data = pd.read_csv('path_to_your_csv_file.csv')

# Calculate the average reading score
average_reading_score = student_data['reading_score'].mean()

print(f'Average reading score: {average_reading_score:.2f}')  # Print with two decimal places
81.87

# Use the following to calculate the percentage of students who passed math (math scores greather than or equal to 70)
passing_math_count = school_data_complete[(school_data_complete["math_score"] >= 70)].count()["student_name"]
passing_math_percentage = passing_math_count / float(student_count) * 100
passing_math_percentage
import pandas as pd

# Assuming you have loaded your data into a DataFrame named student_data
# For example:
# student_data = pd.read_csv('path_to_your_csv_file.csv')

# Define passing math score threshold
passing_math_score = 70

# Calculate the percentage of students who passed math
num_students_passed_math = student_data[student_data['math_score'] >= passing_math_score]['math_score'].count()
total_students = student_data['math_score'].count()
percent_passed_math = (num_students_passed_math / total_students) * 100

print(f'Percentage of students who passed math: {percent_passed_math:.2f}%')  # Print with two decimal places
74.98

# Calculate the percentage of students who passed reading (hint: look at how the math percentage was calculated)
passing_reading_count =
passing_reading_percentage =
import pandas as pd

# Assuming you have loaded your data into a DataFrame named student_data
# For example:
# student_data = pd.read_csv('path_to_your_csv_file.csv')

# Define passing reading score threshold
passing_reading_score = 70

# Calculate the percentage of students who passed reading
num_students_passed_reading = student_data[student_data['reading_score'] >= passing_reading_score]['reading_score'].count()
total_students = student_data['reading_score'].count()
percent_passed_reading = (num_students_passed_reading / total_students) * 100

print(f'Percentage of students who passed reading: {percent_passed_reading:.2f}%')  # Print with two decimal places

# Use the following to calculate the percentage of students that passed math and reading
passing_math_reading_count = school_data_complete[
    (school_data_complete["math_score"] >= 70) & (school_data_complete["reading_score"] >= 70)
].count()["student_name"]
overall_passing_rate = passing_math_reading_count /  float(student_count) * 100
overall_passing_rate
import pandas as pd

# Assuming you have loaded your data into a DataFrame named student_data
# For example:
# student_data = pd.read_csv('path_to_your_csv_file.csv')

# Define passing score thresholds
passing_math_score = 70
passing_reading_score = 70

# Calculate the number of students who passed both math and reading
passed_math = student_data['math_score'] >= passing_math_score
passed_reading = student_data['reading_score'] >= passing_reading_score
num_students_passed_both = student_data[passed_math & passed_reading]['Student ID'].count()

# Calculate the total number of students
total_students = student_data['Student ID'].count()

# Calculate the overall passing percentage
percent_passed_both = (num_students_passed_both / total_students) * 100

print(f'Overall passing percentage (both math and reading): {percent_passed_both:.2f}%')  # Print with two decimal places
65.17

# Create a high-level snapshot of the district's key metrics in a DataFrame
district_summary =

# Formatting
district_summary["Total Students"] = district_summary["Total Students"].map("{:,}".format)
district_summary["Total Budget"] = district_summary["Total Budget"].map("${:,.2f}".format)

# Display the DataFrame
district_summary

Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	        15	39,170	        $24,649,428.00	78.985371	81.87784	74.980853	            85.805463	                65.172326

# Use the code provided to select the type per school from school_data
school_types = school_data.set_index(["school_name"])["type"]

import pandas as pd

# Assuming you have loaded your data into a DataFrame named school_data
# For example:
# school_data = pd.read_csv('path_to_your_csv_file.csv')

# Calculate the total number of unique schools
total_schools = school_data['school_name'].nunique()

print(f'Total number of unique schools: {total_schools}')

# Calculate the total student count per school from school_data
per_school_counts =
school_count
import pandas as pd

# Assuming you have loaded your data into a DataFrame named school_data
# Example assuming the data structure
# school_data = pd.read_csv('path_to_your_csv_file.csv')

# Group by school_name and calculate total student count
total_students_per_school = school_data.groupby('school_name')['size'].sum()

print(total_students_per_school)

# Calculate the total school budget and per capita spending per school from school_data
per_school_budget =
per_school_capita =
import pandas as pd

# Assuming you have loaded your data into a DataFrame named school_data
# Example assuming the data structure
# school_data = pd.read_csv('path_to_your_csv_file.csv')

# Calculate total school budget
total_school_budget = school_data.groupby('school_name')['budget'].sum()

# Calculate per capita spending (per student budget)
school_data['Per Student Budget'] = school_data['budget'] / school_data['size']

# Display the results
print("Total School Budget:")
print(total_school_budget)
print("\nPer Student Budget:")
print(school_data[['school_name', 'Per Student Budget']].set_index('school_name'))

# Calculate the average test scores per school from school_data_complete
per_school_math =
per_school_reading =
import pandas as pd

# Assuming you have loaded your data into a DataFrame named school_data_complete
# Example assuming the data structure
# school_data_complete = pd.read_csv('path_to_your_csv_file.csv')

# Calculate average math score per school
average_math_score_per_school = school_data_complete.groupby('school_name')['math_score'].mean()

# Calculate average reading score per school
average_reading_score_per_school = school_data_complete.groupby('school_name')['reading_score'].mean()

# Display the results
print("Average Math Score per School:")
print(average_math_score_per_school)
print("\nAverage Reading Score per School:")
print(average_reading_score_per_school)

# Calculate the number of students per school with math scores of 70 or higher from school_data_complete
students_passing_math =
school_students_passing_math =
import pandas as pd

# Assuming you have loaded your data into a DataFrame named school_data_complete
# Example assuming the data structure
# school_data_complete = pd.read_csv('path_to_your_csv_file.csv')

# Define passing math score threshold
passing_math_score = 70

# Filter students who passed math (scored 70 or higher)
passing_math_students = school_data_complete[school_data_complete['math_score'] >= passing_math_score]

# Count number of passing math students per school
passing_math_count_per_school = passing_math_students.groupby('school_name')['Student ID'].count()

# Display the results
print("Number of Students per School with Math Scores of 70 or Higher:")
print(passing_math_count_per_school)

# Calculate the number of students per school with reading scores of 70 or higher from school_data_complete
students_passing_reading =
school_students_passing_reading =
import pandas as pd

# Assuming you have loaded your data into a DataFrame named school_data_complete
# Example assuming the data structure
# school_data_complete = pd.read_csv('path_to_your_csv_file.csv')

# Define passing reading score threshold
passing_reading_score = 70

# Filter students who passed reading (scored 70 or higher)
passing_reading_students = school_data_complete[school_data_complete['reading_score'] >= passing_reading_score]

# Count number of passing reading students per school
passing_reading_count_per_school = passing_reading_students.groupby('school_name')['Student ID'].count()

# Display the results
print("Number of Students per School with Reading Scores of 70 or Higher:")
print(passing_reading_count_per_school)

# Use the provided code to calculate the number of students per school that passed both math and reading with scores of 70 or higher
students_passing_math_and_reading = school_data_complete[
    (school_data_complete["reading_score"] >= 70) & (school_data_complete["math_score"] >= 70)
]
school_students_passing_math_and_reading = students_passing_math_and_reading.groupby(["school_name"]).size()
import pandas as pd

# Assuming you have loaded your data into a DataFrame named school_data_complete
# Example assuming the data structure
# school_data_complete = pd.read_csv('path_to_your_csv_file.csv')

# Define passing score thresholds
passing_math_score = 70
passing_reading_score = 70

# Filter students who passed both math and reading (scored 70 or higher)
passing_both = school_data_complete[(school_data_complete['math_score'] >= passing_math_score) & (school_data_complete['reading_score'] >= passing_reading_score)]

# Count number of passing both students per school
passing_both_count_per_school = passing_both.groupby('school_name')['Student ID'].count()

# Display the results
print("Number of Students per School that Passed Both Math and Reading with Scores of 70 or Higher:")
print(passing_both_count_per_school)

# Use the provided code to calculate the passing rates
per_school_passing_math = school_students_passing_math / per_school_counts * 100
per_school_passing_reading = school_students_passing_reading / per_school_counts * 100
overall_passing_rate = school_students_passing_math_and_reading / per_school_counts * 100
import pandas as pd

# Assuming you have loaded your data into a DataFrame named school_data_complete
# Example assuming the data structure
# school_data_complete = pd.read_csv('path_to_your_csv_file.csv')

# Define passing score thresholds
passing_math_score = 70
passing_reading_score = 70

# Calculate passing math rates per school
school_data_complete['Passed Math'] = school_data_complete['math_score'] >= passing_math_score
passing_math_rates = school_data_complete.groupby('school_name')['Passed Math'].mean() * 100

# Calculate passing reading rates per school
school_data_complete['Passed Reading'] = school_data_complete['reading_score'] >= passing_reading_score
passing_reading_rates = school_data_complete.groupby('school_name')['Passed Reading'].mean() * 100

# Calculate overall passing rates per school
school_data_complete['Passed Both'] = school_data_complete['Passed Math'] & school_data_complete['Passed Reading']
overall_passing_rates = school_data_complete.groupby('school_name')['Passed Both'].mean() * 100

# Display the results
print("Passing Rates per School:")
print("Passing Math Rates:")
print(passing_math_rates)
print("\nPassing Reading Rates:")
print(passing_reading_rates)
print("\nOverall Passing Rates:")
print(overall_passing_rates)

# Create a DataFrame called `per_school_summary` with columns for the calculations above.
per_school_summary =

import pandas as pd

# Assuming you have loaded your data into DataFrames named school_data and school_data_complete
# Example assuming the data structure
# school_data = pd.read_csv('path_to_school_data_file.csv')
# school_data_complete = pd.read_csv('path_to_school_data_complete_file.csv')

# Calculate total students and budget per school from school_data
total_students_per_school = school_data.groupby('school_name')['size'].sum()
total_budget_per_school = school_data.groupby('school_name')['budget'].sum()
per_student_budget = total_budget_per_school / total_students_per_school

# Calculate average math and reading scores per school
average_math_score_per_school = school_data_complete.groupby('school_name')['math_score'].mean()
average_reading_score_per_school = school_data_complete.groupby('school_name')['reading_score'].mean()

# Calculate passing rates per school
school_data_complete['Passed Math'] = school_data_complete['math_score'] >= 70
school_data_complete['Passed Reading'] = school_data_complete['reading_score'] >= 70
school_data_complete['Passed Both'] = school_data_complete['Passed Math'] & school_data_complete['Passed Reading']

passing_math_rates = school_data_complete.groupby('school_name')['Passed Math'].mean() * 100
passing_reading_rates = school_data_complete.groupby('school_name')['Passed Reading'].mean() * 100
overall_passing_rates = school_data_complete.groupby('school_name')['Passed Both'].mean() * 100

# Combine all metrics into a single DataFrame
per_school_summary = pd.DataFrame({
    'Total Students': total_students_per_school,
    'Total Budget': total_budget_per_school,
    'Per Student Budget': per_student_budget,
    'Average Math Score': average_math_score_per_school,
    'Average Reading Score': average_reading_score_per_school,
    '% Passing Math': passing_math_rates,
    '% Passing Reading': passing_reading_rates,
    '% Overall Passing': overall_passing_rates
})

# Display the DataFrame
print("Per School Summary:")
print(per_school_summary)

# Formatting
per_school_summary["Total School Budget"] = per_school_summary["Total School Budget"].map("${:,.2f}".format)
per_school_summary["Per Student Budget"] = per_school_summary["Per Student Budget"].map("${:,.2f}".format)

# Display the DataFrame
per_school_summary

	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Bailey High School	District	  4976	     $3,124,928.00	    $628.00	  77.048432	          81.033963	            66.680064	      81.933280	        54.642283
Cabrera High School	Charter	    1858	    $1,081,356.00	      $582.00	  83.061895	          83.975780	            94.133477	      97.039828	        91.334769
Figueroa High School	District	2949	    $1,884,411.00	      $639.00	  76.711767	          81.158020	            65.988471	      80.739234	        53.204476
Ford High School	District	    2739	    $1,763,916.00	      $644.00	  77.102592	          80.746258	            68.309602	      79.299014	        54.289887
Griffin High School	Charter	    1468	    $917,500.00	        $625.00	   83.351499	        83.816757	            93.392371	      97.138965	        90.599455
Hernandez High School	District	4635	    $3,022,020.00	      $652.00	   77.289752	        80.934412	            66.752967	      80.862999	        53.527508
Holden High School	Charter	    427	      $248,087.00	        $581.00	   83.803279	        83.814988	            92.505855	      96.252927	        89.227166
Huang High School	District	    2917	    $1,910,635.00	      $655.00	   76.629414	        81.182722	            65.683922	      81.316421	        53.513884
Johnson High School	District	  4761	    $3,094,650.00	      $650.00	  77.072464	          80.966394	            66.057551	      81.222432	        53.539172
Pena High School	Charter	      962	      $585,858.00	        $609.00	   83.839917	        84.044699	            94.594595	      95.945946	        90.540541
Rodriguez High School	District	3999	    $2,547,363.00	      $637.00	   76.842711	        80.744686	            66.366592	      80.220055	        52.988247
Shelton High School	Charter	    1761	    $1,056,600.00	      $600.00	   83.359455	        83.725724	            93.867121	      95.854628	        89.892107  
Thomas High School	Charter	    1635	    $1,043,130.00	      $638.00	   83.418349	        83.848930	            93.272171	      97.308869	        90.948012
Wilson High School	Charter	    2283	    $1,319,574.00	      $578.00	   83.274201	        83.989488	            93.867718	      96.539641	        90.582567
Wright High School	Charter	    1800	    $1,049,400.00	      $583.00	   83.682222	        83.955000	            93.333333	      96.611111	        90.333333

# Sort the schools by `% Overall Passing` in descending order and display the top 5 rows.
top_schools =
top_schools.head(5)
import pandas as pd

# Assuming `per_school_summary` DataFrame has been created with the required columns

# Sort the DataFrame by `% Overall Passing` in descending order
sorted_per_school_summary = per_school_summary.sort_values(by='% Overall Passing', ascending=False)

# Display the top 5 rows
top_schools = sorted_per_school_summary.head(5)

print("Top 5 Schools by Overall Passing Percentage:")
print(top_schools)

	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Cabrera High School	Charter	1858	$1,081,356.00	$582.00	83.061895	83.975780	94.133477	97.039828	91.334769
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.418349	83.848930	93.272171	97.308869	90.948012
Griffin High School	Charter	1468	$917,500.00	$625.00	83.351499	83.816757	93.392371	97.138965	90.599455
Wilson High School	Charter	2283	$1,319,574.00	$578.00	83.274201	83.989488	93.867718	96.539641	90.582567
Pena High School	Charter	962	$585,858.00	$609.00	83.839917	84.044699	94.594595	95.945946	90.540541

# Sort the schools by `% Overall Passing` in ascending order and display the top 5 rows.
bottom_schools =
bottom_schools.head(5)
import pandas as pd

# Assuming `per_school_summary` DataFrame has been created with the required columns

# Sort the DataFrame by `% Overall Passing` in ascending order
sorted_per_school_summary_ascending = per_school_summary.sort_values(by='% Overall Passing', ascending=True)

# Display the top 5 rows
bottom_schools = sorted_per_school_summary_ascending.head(5)

print("Bottom 5 Schools by Overall Passing Percentage:")
print(bottom_schools)

	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Rodriguez High School	District	3999	$2,547,363.00	$637.00	76.842711	80.744686	66.366592	80.220055	52.988247
Figueroa High School	District	2949	$1,884,411.00	$639.00	76.711767	81.158020	65.988471	80.739234	53.204476
Huang High School	District	2917	$1,910,635.00	$655.00	76.629414	81.182722	65.683922	81.316421	53.513884
Hernandez High School	District	4635	$3,022,020.00	$652.00	77.289752	80.934412	66.752967	80.862999	53.527508
Johnson High School	District	4761	$3,094,650.00	$650.00	77.072464	80.966394	66.057551	81.222432	53.539172

# Use the code provided to separate the data by grade
ninth_graders = school_data_complete[(school_data_complete["grade"] == "9th")]
tenth_graders = school_data_complete[(school_data_complete["grade"] == "10th")]
eleventh_graders = school_data_complete[(school_data_complete["grade"] == "11th")]
twelfth_graders = school_data_complete[(school_data_complete["grade"] == "12th")]
import pandas as pd

# Load your data into DataFrame
# school_data_complete = pd.read_csv('path_to_your_csv_file.csv')

# Calculate the average math score for each grade level at each school
math_scores_by_grade = school_data_complete.groupby(['school_name', 'grade'])['math_score'].mean().unstack()

# Calculate the average reading score for each grade level at each school
reading_scores_by_grade = school_data_complete.groupby(['school_name', 'grade'])['reading_score'].mean().unstack()

# Display the DataFrames
print("Average Math Scores by Grade:")
print(math_scores_by_grade)

print("\nAverage Reading Scores by Grade:")
print(reading_scores_by_grade)


# Group by `school_name` and take the mean of the `math_score` column for each.
ninth_grade_math_scores =
tenth_grader_math_scores =
eleventh_grader_math_scores =
twelfth_grader_math_scores =
import pandas as pd

# Load your data into DataFrame
# school_data_complete = pd.read_csv('path_to_your_csv_file.csv')

# Calculate the average math score for each school
average_math_scores_per_school = school_data_complete.groupby('school_name')['math_score'].mean()

# Display the results
print("Average Math Scores per School:")
print(average_math_scores_per_school)

# Combine each of the scores above into single DataFrame called `math_scores_by_grade`
math_scores_by_grade =
import pandas as pd

# Load your data into DataFrame
# school_data_complete = pd.read_csv('path_to_your_csv_file.csv')

# Calculate the average math score for each grade level at each school
math_scores_by_grade = school_data_complete.groupby(['school_name', 'grade'])['math_score'].mean().unstack()

# Display the DataFrame
print("Average Math Scores by Grade:")
print(math_scores_by_grade)

# Minor data wrangling
math_scores_by_grade.index.name = None
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School A', 'School B', 'School B'],
    'grade': ['9th', '10th', '9th', '10th'],
    'math_score': [88, 92, 79, 85]
}

# Create DataFrame
school_data_complete = pd.DataFrame(data)

# Calculate average math scores by grade
math_scores_by_grade = school_data_complete.groupby(['school_name', 'grade'])['math_score'].mean().unstack()

# Minor data wrangling
# Fill missing values with 0
math_scores_by_grade_filled = math_scores_by_grade.fillna(0)

# Rename columns for consistency
math_scores_by_grade_renamed = math_scores_by_grade.rename(columns={
    '9th': 'Grade 9',
    '10th': 'Grade 10'
})

# Round math scores to 2 decimal places
math_scores_by_grade_rounded = math_scores_by_grade_renamed.round(2)

# Add an average score column
math_scores_by_grade_rounded['Average Score'] = math_scores_by_grade_rounded.mean(axis=1)

# Display the results
print("Average Math Scores by Grade (After Wrangling):")
print(math_scores_by_grade_rounded)

# Display the DataFrame
math_scores_by_grade

	9th	10th	11th	12th
Bailey High School	77.083676	76.996772	77.515588	76.492218
Cabrera High School	83.094697	83.154506	82.765560	83.277487
Figueroa High School	76.403037	76.539974	76.884344	77.151369
Ford High School	77.361345	77.672316	76.918058	76.179963
Griffin High School	82.044010	84.229064	83.842105	83.356164
Hernandez High School	77.438495	77.337408	77.136029	77.186567
Holden High School	83.787402	83.429825	85.000000	82.855422
Huang High School	77.027251	75.908735	76.446602	77.225641
Johnson High School	77.187857	76.691117	77.491653	76.863248
Pena High School	83.625455	83.372000	84.328125	84.121547
Rodriguez High School	76.859966	76.612500	76.395626	77.690748
Shelton High School	83.420755	82.917411	83.383495	83.778976
Thomas High School	83.590022	83.087886	83.498795	83.497041
Wilson High School	83.085578	83.724422	83.195326	83.035794
Wright High School	83.264706	84.010288	83.836782	83.644986

# Use the code provided to separate the data by grade
ninth_graders = school_data_complete[(school_data_complete["grade"] == "9th")]
tenth_graders = school_data_complete[(school_data_complete["grade"] == "10th")]
eleventh_graders = school_data_complete[(school_data_complete["grade"] == "11th")]
twelfth_graders = school_data_complete[(school_data_complete["grade"] == "12th")]
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School A', 'School B', 'School B', 'School A', 'School B'],
    'grade': ['9th', '10th', '9th', '10th', '11th', '11th'],
    'math_score': [88, 92, 79, 85, 91, 78],
    'reading_score': [84, 89, 82, 87, 90, 80]
}

# Create DataFrame
school_data_complete = pd.DataFrame(data)
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School A', 'School B', 'School B', 'School A', 'School B'],
    'grade': ['9th', '10th', '9th', '10th', '11th', '11th'],
    'math_score': [88, 92, 79, 85, 91, 78],
    'reading_score': [84, 89, 82, 87, 90, 80]
}

# Create DataFrame
school_data_complete = pd.DataFrame(data)

# Calculate average math scores for each grade level at each school
math_scores_by_grade = school_data_complete.groupby(['school_name', 'grade'])['math_score'].mean().unstack()

# Calculate average reading scores for each grade level at each school
reading_scores_by_grade = school_data_complete.groupby(['school_name', 'grade'])['reading_score'].mean().unstack()

# Combine the two DataFrames on the school_name index
combined_scores_by_grade = pd.concat([math_scores_by_grade, reading_scores_by_grade], axis=1, keys=['Math', 'Reading'])

# Flatten MultiIndex columns
combined_scores_by_grade.columns = [f'{col[0]} {col[1]}' for col in combined_scores_by_grade.columns]

# Display the combined DataFrame
print("Combined Average Scores by Grade:")
print(combined_scores_by_grade)

# Group by `school_name` and take the mean of the the `reading_score` column for each.
ninth_grade_reading_scores =
tenth_grader_reading_scores =
eleventh_grader_reading_scores =
twelfth_grader_reading_scores =
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School A', 'School B', 'School B', 'School A', 'School B'],
    'reading_score': [84, 89, 82, 87, 90, 80]
}

# Create DataFrame
school_data_complete = pd.DataFrame(data)

# Group by 'school_name' and calculate the mean of 'reading_score'
average_reading_scores = school_data_complete.groupby('school_name')['reading_score'].mean()

# Convert the result to a DataFrame for better readability
average_reading_scores_df = average_reading_scores.reset_index()

# Rename columns for clarity
average_reading_scores_df.columns = ['School Name', 'Average Reading Score']

# Display the DataFrame
print("Average Reading Scores by School:")
print(average_reading_scores_df)

# Combine each of the scores above into single DataFrame called `reading_scores_by_grade`
reading_scores_by_grade =
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School A', 'School B', 'School B', 'School A', 'School B'],
    'grade': ['9th', '10th', '9th', '10th', '11th', '11th'],
    'reading_score': [84, 89, 82, 87, 90, 80]
}

# Create DataFrame
school_data_complete = pd.DataFrame(data)

# Group by 'school_name' and 'grade', then calculate the mean of 'reading_score'
average_reading_scores_by_grade = school_data_complete.groupby(['school_name', 'grade'])['reading_score'].mean().unstack()

# Display the DataFrame
print("Average Reading Scores by Grade:")
print(average_reading_scores_by_grade)

# Minor data wrangling
reading_scores_by_grade = reading_scores_by_grade[["9th", "10th", "11th", "12th"]]
reading_scores_by_grade.index.name = None
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School A', 'School B', 'School B', 'School A', 'School B'],
    'grade': ['9th', '10th', '9th', '10th', '11th', '11th'],
    'reading_score': [84, 89, 82, 87, 90, 80]
}

# Create DataFrame
school_data_complete = pd.DataFrame(data)

# Group by 'school_name' and 'grade', then calculate the mean of 'reading_score'
average_reading_scores_by_grade = school_data_complete.groupby(['school_name', 'grade'])['reading_score'].mean().unstack()

# Minor data wrangling

# 1. Clean column names (e.g., remove leading/trailing spaces, convert to lowercase)
average_reading_scores_by_grade.columns = average_reading_scores_by_grade.columns.str.strip().str.lower()

# 2. Handle missing values (e.g., fill NaNs with a placeholder or method of choice)
average_reading_scores_by_grade = average_reading_scores_by_grade.fillna('No Data')

# 3. Sort the DataFrame (e.g., sort by the average reading score in a specific grade)
# Sort by '9th' grade reading scores
average_reading_scores_by_grade = average_reading_scores_by_grade.sort_values(by='9th', ascending=False)

# 4. Reformat index (e.g., reset index if needed)
average_reading_scores_by_grade = average_reading_scores_by_grade.reset_index()

# Display the cleaned DataFrame
print("Cleaned Average Reading Scores by Grade:")
print(average_reading_scores_by_grade)

# Display the DataFrame
reading_scores_by_grade

	9th	10th	11th	12th
Bailey High School	81.303155	80.907183	80.945643	80.912451
Cabrera High School	83.676136	84.253219	83.788382	84.287958
Figueroa High School	81.198598	81.408912	80.640339	81.384863
Ford High School	80.632653	81.262712	80.403642	80.662338
Griffin High School	83.369193	83.706897	84.288089	84.013699
Hernandez High School	80.866860	80.660147	81.396140	80.857143
Holden High School	83.677165	83.324561	83.815534	84.698795
Huang High School	81.290284	81.512386	81.417476	80.305983
Johnson High School	81.260714	80.773431	80.616027	81.227564
Pena High School	83.807273	83.612000	84.335938	84.591160
Rodriguez High School	80.993127	80.629808	80.864811	80.376426
Shelton High School	84.122642	83.441964	84.373786	82.781671
Thomas High School	83.728850	84.254157	83.585542	83.831361
Wilson High School	83.939778	84.021452	83.764608	84.317673
Wright High School	83.833333	83.812757	84.156322	84.073171

# Establish the bins
spending_bins = [0, 585, 630, 645, 680]
labels = ["<$585", "$585-630", "$630-645", "$645-680"]
import pandas as pd

# Example data for demonstration
school_data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'total_budget': [1000000, 500000, 750000, 1200000],
    'total_students': [1000, 1500, 2000, 500]
}

# Create DataFrame
school_data_df = pd.DataFrame(school_data)

# Define bins and labels for spending ranges
spending_bins = [0, 585000, 630000, 645000, 680000]
spending_labels = ["<$585K", "$585K-630K", "$630K-645K", "$645K-680K"]

# Calculate per-student budget
school_data_df['per_student_budget'] = school_data_df['total_budget'] / school_data_df['total_students']

# Bin the per-student budget
school_data_df['Spending Ranges (Per Student)'] = pd.cut(school_data_df['per_student_budget'], bins=spending_bins, labels=spending_labels)

# Display the DataFrame with spending ranges
print("DataFrame with Spending Ranges:")
print(school_data_df)

# Create a copy of the school summary since it has the "Per Student Budget"
school_spending_df = per_school_summary.copy()
import pandas as pd

# Example data for demonstration
school_summary = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'total_students': [1000, 1500, 2000, 500],
    'total_budget': [1000000, 500000, 750000, 1200000]
}

# Create DataFrame
school_summary_df = pd.DataFrame(school_summary)

# Calculate Per Student Budget
school_summary_df['per_student_budget'] = school_summary_df['total_budget'] / school_summary_df['total_students']

# Create a copy of the school summary DataFrame
school_summary_copy = school_summary_df.copy()

# Display the copied DataFrame
print("Copied School Summary DataFrame:")
print(school_summary_copy)

# Use `pd.cut` to categorize spending based on the bins.
school_spending_df["Spending Ranges (Per Student)"] =
school_spending_df
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'total_budget': [1000000, 500000, 750000, 1200000],
    'total_students': [1000, 1500, 2000, 500]
}

# Create DataFrame
school_summary_df = pd.DataFrame(data)

# Calculate Per Student Budget
school_summary_df['per_student_budget'] = school_summary_df['total_budget'] / school_summary_df['total_students']

# Define bins and labels for spending ranges
spending_bins = [0, 585000, 630000, 645000, 680000]
spending_labels = ["<$585K", "$585K-630K", "$630K-645K", "$645K-680K"]

# Bin the per-student budget
school_summary_df['Spending Ranges (Per Student)'] = pd.cut(school_summary_df['per_student_budget'], bins=spending_bins, labels=spending_labels)

# Display the DataFrame with spending ranges
print("DataFrame with Spending Ranges:")
print(school_summary_df)

	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing	Spending Ranges (Per Student)
Bailey High School	District	4976	$3,124,928.00	$628.00	77.048432	81.033963	66.680064	81.933280	54.642283	$585-630
Cabrera High School	Charter	1858	$1,081,356.00	$582.00	83.061895	83.975780	94.133477	97.039828	91.334769	<$585
Figueroa High School	District	2949	$1,884,411.00	$639.00	76.711767	81.158020	65.988471	80.739234	53.204476	$630-645
Ford High School	District	2739	$1,763,916.00	$644.00	77.102592	80.746258	68.309602	79.299014	54.289887	$630-645
Griffin High School	Charter	1468	$917,500.00	$625.00	83.351499	83.816757	93.392371	97.138965	90.599455	$585-630
Hernandez High School	District	4635	$3,022,020.00	$652.00	77.289752	80.934412	66.752967	80.862999	53.527508	$645-680
Holden High School	Charter	427	$248,087.00	$581.00	83.803279	83.814988	92.505855	96.252927	89.227166	<$585
Huang High School	District	2917	$1,910,635.00	$655.00	76.629414	81.182722	65.683922	81.316421	53.513884	$645-680
Johnson High School	District	4761	$3,094,650.00	$650.00	77.072464	80.966394	66.057551	81.222432	53.539172	$645-680
Pena High School	Charter	962	$585,858.00	$609.00	83.839917	84.044699	94.594595	95.945946	90.540541	$585-630
Rodriguez High School	District	3999	$2,547,363.00	$637.00	76.842711	80.744686	66.366592	80.220055	52.988247	$630-645
Shelton High School	Charter	1761	$1,056,600.00	$600.00	83.359455	83.725724	93.867121	95.854628	89.892107	$585-630
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.418349	83.848930	93.272171	97.308869	90.948012	$630-645
Wilson High School	Charter	2283	$1,319,574.00	$578.00	83.274201	83.989488	93.867718	96.539641	90.582567	<$585
Wright High School	Charter	1800	$1,049,400.00	$583.00	83.682222	83.955000	93.333333	96.611111	90.333333	<$585

#  Calculate averages for the desired columns.
spending_math_scores = school_spending_df.groupby(["Spending Ranges (Per Student)"])["Average Math Score"].mean()
spending_reading_scores = school_spending_df.groupby(["Spending Ranges (Per Student)"])["Average Reading Score"].mean()
spending_passing_math = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Passing Math"].mean()
spending_passing_reading = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Passing Reading"].mean()
overall_passing_spending = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Overall Passing"].mean()

import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'per_student_budget': [1000.0, 333.3, 375.0, 2400.0],
    'Average Math Score': [85, 78, 80, 90],
    'Average Reading Score': [88, 82, 84, 92],
    '% Passing Math': [90, 75, 80, 95],
    '% Passing Reading': [92, 80, 85, 98],
    '% Overall Passing': [85, 70, 75, 93]
}

# Create DataFrame
school_spending_df = pd.DataFrame(data)

# Define bins and labels for spending ranges
spending_bins = [0, 585, 630, 645, 680]
spending_labels = ["<$585", "$585-630", "$630-645", "$645-680"]

# Bin the per-student budget
school_spending_df['Spending Ranges (Per Student)'] = pd.cut(school_spending_df['per_student_budget'], bins=spending_bins, labels=spending_labels)

# Calculate the averages
spending_math_scores = school_spending_df.groupby(["Spending Ranges (Per Student)"])["Average Math Score"].mean()
spending_reading_scores = school_spending_df.groupby(["Spending Ranges (Per Student)"])["Average Reading Score"].mean()
spending_passing_math = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Passing Math"].mean()
spending_passing_reading = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Passing Reading"].mean()
overall_passing_spending = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Overall Passing"].mean()

# Combine into a single DataFrame
spending_summary = pd.DataFrame({
    "Average Math Score": spending_math_scores,
    "Average Reading Score": spending_reading_scores,
    "% Passing Math": spending_passing_math,
    "% Passing Reading": spending_passing_reading,
    "% Overall Passing": overall_passing_spending
})

# Display the spending summary DataFrame
print("Spending Summary DataFrame:")
print(spending_summary)

# Assemble into DataFrame
spending_summary =

import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'per_student_budget': [1000.0, 333.3, 375.0, 2400.0],
    'Average Math Score': [85, 78, 80, 90],
    'Average Reading Score': [88, 82, 84, 92],
    '% Passing Math': [90, 75, 80, 95],
    '% Passing Reading': [92, 80, 85, 98],
    '% Overall Passing': [85, 70, 75, 93]
}

# Create DataFrame
school_spending_df = pd.DataFrame(data)

# Define bins and labels for spending ranges
spending_bins = [0, 585, 630, 645, 680]
spending_labels = ["<$585", "$585-630", "$630-645", "$645-680"]

# Bin the per-student budget
school_spending_df['Spending Ranges (Per Student)'] = pd.cut(school_spending_df['per_student_budget'], bins=spending_bins, labels=spending_labels)

# Calculate the averages
spending_math_scores = school_spending_df.groupby(["Spending Ranges (Per Student)"])["Average Math Score"].mean()
spending_reading_scores = school_spending_df.groupby(["Spending Ranges (Per Student)"])["Average Reading Score"].mean()
spending_passing_math = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Passing Math"].mean()
spending_passing_reading = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Passing Reading"].mean()
overall_passing_spending = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Overall Passing"].mean()

# Assemble into DataFrame
spending_summary = pd.DataFrame({
    "Average Math Score": spending_math_scores,
    "Average Reading Score": spending_reading_scores,
    "% Passing Math": spending_passing_math,
    "% Passing Reading": spending_passing_reading,
    "% Overall Passing": overall_passing_spending
})

# Display the spending summary DataFrame
print("Spending Summary DataFrame:")
print(spending_summary)

# Display results
spending_summary

	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Spending Ranges (Per Student)					
<$585	83.455399	83.933814	93.460096	96.610877	90.369459
$585-630	81.899826	83.155286	87.133538	92.718205	81.418596
$630-645	78.518855	81.624473	73.484209	84.391793	62.857656
$645-680	76.997210	81.027843	66.164813	81.133951	53.526855

# Establish the bins.
size_bins = [0, 1000, 2000, 5000]
labels = ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"]
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'total_students': [500, 1500, 2500, 4500]
}

# Create DataFrame
school_summary_df = pd.DataFrame(data)

# Define bins and labels for school size categories
size_bins = [0, 1000, 2000, 5000]
size_labels = ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"]

# Bin the total students to categorize school size
school_summary_df['School Size'] = pd.cut(school_summary_df['total_students'], bins=size_bins, labels=size_labels)

# Display the DataFrame with school size categories
print("DataFrame with School Size Categories:")
print(school_summary_df)

# Categorize the spending based on the bins
# Use `pd.cut` on the "Total Students" column of the `per_school_summary` DataFrame.

per_school_summary["School Size"] =
per_school_summary
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'Total Students': [500, 1500, 2500, 4500],
    'Average Math Score': [85, 78, 80, 90],
    'Average Reading Score': [88, 82, 84, 92],
    '% Passing Math': [90, 75, 80, 95],
    '% Passing Reading': [92, 80, 85, 98],
    '% Overall Passing': [85, 70, 75, 93]
}

# Create DataFrame
per_school_summary = pd.DataFrame(data)

# Define bins and labels for school size categories
size_bins = [0, 1000, 2000, 5000]
size_labels = ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"]

# Use `pd.cut` to categorize the "Total Students" into size categories
per_school_summary["School Size"] = pd.cut(per_school_summary["Total Students"], bins=size_bins, labels=size_labels)

# Display the updated DataFrame
print("Updated per_school_summary DataFrame with School Size:")
print(per_school_summary)

	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing	School Size
Bailey High School	District	4976	$3,124,928.00	$628.00	77.048432	81.033963	66.680064	81.933280	54.642283	Large (2000-5000)
Cabrera High School	Charter	1858	$1,081,356.00	$582.00	83.061895	83.975780	94.133477	97.039828	91.334769	Medium (1000-2000)
Figueroa High School	District	2949	$1,884,411.00	$639.00	76.711767	81.158020	65.988471	80.739234	53.204476	Large (2000-5000)
Ford High School	District	2739	$1,763,916.00	$644.00	77.102592	80.746258	68.309602	79.299014	54.289887	Large (2000-5000)
Griffin High School	Charter	1468	$917,500.00	$625.00	83.351499	83.816757	93.392371	97.138965	90.599455	Medium (1000-2000)
Hernandez High School	District	4635	$3,022,020.00	$652.00	77.289752	80.934412	66.752967	80.862999	53.527508	Large (2000-5000)
Holden High School	Charter	427	$248,087.00	$581.00	83.803279	83.814988	92.505855	96.252927	89.227166	Small (<1000)
Huang High School	District	2917	$1,910,635.00	$655.00	76.629414	81.182722	65.683922	81.316421	53.513884	Large (2000-5000)
Johnson High School	District	4761	$3,094,650.00	$650.00	77.072464	80.966394	66.057551	81.222432	53.539172	Large (2000-5000)
Pena High School	Charter	962	$585,858.00	$609.00	83.839917	84.044699	94.594595	95.945946	90.540541	Small (<1000)
Rodriguez High School	District	3999	$2,547,363.00	$637.00	76.842711	80.744686	66.366592	80.220055	52.988247	Large (2000-5000)
Shelton High School	Charter	1761	$1,056,600.00	$600.00	83.359455	83.725724	93.867121	95.854628	89.892107	Medium (1000-2000)
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.418349	83.848930	93.272171	97.308869	90.948012	Medium (1000-2000)
Wilson High School	Charter	2283	$1,319,574.00	$578.00	83.274201	83.989488	93.867718	96.539641	90.582567	Large (2000-5000)
Wright High School	Charter	1800	$1,049,400.00	$583.00	83.682222	83.955000	93.333333	96.611111	90.333333	Medium (1000-2000)

# Calculate averages for the desired columns.
size_math_scores = per_school_summary.groupby(["School Size"])["Average Math Score"].mean()
size_reading_scores = per_school_summary.groupby(["School Size"])["Average Reading Score"].mean()
size_passing_math = per_school_summary.groupby(["School Size"])["% Passing Math"].mean()
size_passing_reading = per_school_summary.groupby(["School Size"])["% Passing Reading"].mean()
size_overall_passing = per_school_summary.groupby(["School Size"])["% Overall Passing"].mean()
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'Total Students': [500, 1500, 2500, 4500]
}

# Create DataFrame
per_school_summary = pd.DataFrame(data)

# Define bins and labels for school size categories
size_bins = [0, 1000, 2000, 5000]
size_labels = ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"]

# Bin the total students to categorize school size
per_school_summary['School Size'] = pd.cut(per_school_summary['Total Students'], bins=size_bins, labels=size_labels)

# Display the DataFrame with school size categories
print("DataFrame with School Size Categories:")
print(per_school_summary)

# Create a DataFrame called `size_summary` that breaks down school performance based on school size (small, medium, or large).
# Use the scores above to create a new DataFrame called `size_summary`
size_summary =
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'Total Students': [500, 1500, 2500, 4500],
    'Average Math Score': [85, 78, 80, 90],
    'Average Reading Score': [88, 82, 84, 92],
    '% Passing Math': [90, 75, 80, 95],
    '% Passing Reading': [92, 80, 85, 98],
    '% Overall Passing': [85, 70, 75, 93]
}

# Create DataFrame
per_school_summary = pd.DataFrame(data)

# Define bins and labels for school size categories
size_bins = [0, 1000, 2000, 5000]
size_labels = ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"]

# Bin the total students to categorize school size
per_school_summary['School Size'] = pd.cut(per_school_summary['Total Students'], bins=size_bins, labels=size_labels)

# Group by 'School Size' and calculate averages for the relevant metrics
size_summary = per_school_summary.groupby('School Size').agg({
    'Average Math Score': 'mean',
    'Average Reading Score': 'mean',
    '% Passing Math': 'mean',
    '% Passing Reading': 'mean',
    '% Overall Passing': 'mean'
})

# Rename columns for clarity
size_summary.columns = [
    'Average Math Score',
    'Average Reading Score',
    '% Passing Math',
    '% Passing Reading',
    '% Overall Passing'
]

# Display the size_summary DataFrame
print("Size Summary DataFrame:")
print(size_summary)

# Display results
size_summary

	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
School Size					
Small (<1000)	83.821598	83.929843	93.550225	96.099437	89.883853
Medium (1000-2000)	83.374684	83.864438	93.599695	96.790680	90.621535
Large (2000-5000)	77.746417	81.344493	69.963361	82.766634	58.286003

# Group the per_school_summary DataFrame by "School Type" and average the results.
average_math_score_by_type = per_school_summary.groupby(["School Type"])["Average Math Score"].mean()
average_reading_score_by_type = per_school_summary.groupby(["School Type"])["Average Reading Score"].mean()
average_percent_passing_math_by_type = per_school_summary.groupby(["School Type"])["% Passing Math"].mean()
average_percent_passing_reading_by_type = per_school_summary.groupby(["School Type"])["% Passing Reading"].mean()
average_percent_overall_passing_by_type = per_school_summary.groupby(["School Type"])["% Overall Passing"].mean()
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'School Type': ['Public', 'Private', 'Public', 'Private'],
    'Average Math Score': [85, 78, 80, 90],
    'Average Reading Score': [88, 82, 84, 92],
    '% Passing Math': [90, 75, 80, 95],
    '% Passing Reading': [92, 80, 85, 98],
    '% Overall Passing': [85, 70, 75, 93]
}

# Create DataFrame
per_school_summary = pd.DataFrame(data)

# Group by "School Type" and calculate averages for each metric
average_math_score_by_type = per_school_summary.groupby("School Type")["Average Math Score"].mean()
average_reading_score_by_type = per_school_summary.groupby("School Type")["Average Reading Score"].mean()
average_percent_passing_math_by_type = per_school_summary.groupby("School Type")["% Passing Math"].mean()
average_percent_passing_reading_by_type = per_school_summary.groupby("School Type")["% Passing Reading"].mean()
average_percent_overall_passing_by_type = per_school_summary.groupby("School Type")["% Overall Passing"].mean()

# Assemble results into a single DataFrame
type_summary = pd.DataFrame({
    'Average Math Score': average_math_score_by_type,
    'Average Reading Score': average_reading_score_by_type,
    '% Passing Math': average_percent_passing_math_by_type,
    '% Passing Reading': average_percent_passing_reading_by_type,
    '% Overall Passing': average_percent_overall_passing_by_type
})

# Display the type_summary DataFrame
print("Type Summary DataFrame:")
print(type_summary)

# Assemble the new data by type into a DataFrame called `type_summary`
type_summary =
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'School Type': ['Public', 'Private', 'Public', 'Private'],
    'Average Math Score': [85, 78, 80, 90],
    'Average Reading Score': [88, 82, 84, 92],
    '% Passing Math': [90, 75, 80, 95],
    '% Passing Reading': [92, 80, 85, 98],
    '% Overall Passing': [85, 70, 75, 93]
}

# Create DataFrame
per_school_summary = pd.DataFrame(data)

# Group by "School Type" and calculate averages for each metric
average_math_score_by_type = per_school_summary.groupby("School Type")["Average Math Score"].mean()
average_reading_score_by_type = per_school_summary.groupby("School Type")["Average Reading Score"].mean()
average_percent_passing_math_by_type = per_school_summary.groupby("School Type")["% Passing Math"].mean()
average_percent_passing_reading_by_type = per_school_summary.groupby("School Type")["% Passing Reading"].mean()
average_percent_overall_passing_by_type = per_school_summary.groupby("School Type")["% Overall Passing"].mean()

# Assemble results into a single DataFrame
type_summary = pd.DataFrame({
    'Average Math Score': average_math_score_by_type,
    'Average Reading Score': average_reading_score_by_type,
    '% Passing Math': average_percent_passing_math_by_type,
    '% Passing Reading': average_percent_passing_reading_by_type,
    '% Overall Passing': average_percent_overall_passing_by_type
})

# Display the type_summary DataFrame
print("Type Summary DataFrame:")
print(type_summary)

# Display results
type_summary

# Assemble the new data by type into a DataFrame called `type_summary`
type_summary =
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'School Type': ['Public', 'Private', 'Public', 'Private'],
    'Average Math Score': [85, 78, 80, 90],
    'Average Reading Score': [88, 82, 84, 92],
    '% Passing Math': [90, 75, 80, 95],
    '% Passing Reading': [92, 80, 85, 98],
    '% Overall Passing': [85, 70, 75, 93]
}

# Create DataFrame
per_school_summary = pd.DataFrame(data)

# Group by "School Type" and calculate averages for each metric
average_math_score_by_type = per_school_summary.groupby("School Type")["Average Math Score"].mean()
average_reading_score_by_type = per_school_summary.groupby("School Type")["Average Reading Score"].mean()
average_percent_passing_math_by_type = per_school_summary.groupby("School Type")["% Passing Math"].mean()
average_percent_passing_reading_by_type = per_school_summary.groupby("School Type")["% Passing Reading"].mean()
average_percent_overall_passing_by_type = per_school_summary.groupby("School Type")["% Overall Passing"].mean()

# Assemble results into a single DataFrame
type_summary = pd.DataFrame({
    'Average Math Score': average_math_score_by_type,
    'Average Reading Score': average_reading_score_by_type,
    '% Passing Math': average_percent_passing_math_by_type,
    '% Passing Reading': average_percent_passing_reading_by_type,
    '% Overall Passing': average_percent_overall_passing_by_type
})

# Display the type_summary DataFrame
print("Type Summary DataFrame:")
print(type_summary)

# Display results
type_summary
# Assemble the new data by type into a DataFrame called `type_summary`
type_summary =
import pandas as pd

# Example data for demonstration
data = {
    'school_name': ['School A', 'School B', 'School C', 'School D'],
    'School Type': ['Public', 'Private', 'Public', 'Private'],
    'Average Math Score': [85, 78, 80, 90],
    'Average Reading Score': [88, 82, 84, 92],
    '% Passing Math': [90, 75, 80, 95],
    '% Passing Reading': [92, 80, 85, 98],
    '% Overall Passing': [85, 70, 75, 93]
}

# Create DataFrame
per_school_summary = pd.DataFrame(data)

# Group by "School Type" and calculate averages for each metric
average_math_score_by_type = per_school_summary.groupby("School Type")["Average Math Score"].mean()
average_reading_score_by_type = per_school_summary.groupby("School Type")["Average Reading Score"].mean()
average_percent_passing_math_by_type = per_school_summary.groupby("School Type")["% Passing Math"].mean()
average_percent_passing_reading_by_type = per_school_summary.groupby("School Type")["% Passing Reading"].mean()
average_percent_overall_passing_by_type = per_school_summary.groupby("School Type")["% Overall Passing"].mean()

# Assemble results into a single DataFrame
type_summary = pd.DataFrame({
    'Average Math Score': average_math_score_by_type,
    'Average Reading Score': average_reading_score_by_type,
    '% Passing Math': average_percent_passing_math_by_type,
    '% Passing Reading': average_percent_passing_reading_by_type,
    '% Overall Passing': average_percent_overall_passing_by_type
})

# Display the type_summary DataFrame
print("Type Summary DataFrame:")
print(type_summary)

# Display results
type_summary

	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
School Type					
Charter	83.473852	83.896421	93.620830	96.586489	90.432244
District	76.956733	80.966636	66.548453	80.799062	53.672208
