# Pandas-Challenge

Pandas is a powerful data analysis Python library and I've used the Pandas Framework to analyse datasets on schools and students.
In this assignment, I've used the Pandas library to make strategic decisions regarding future school budgets and priorities along with analyzing the district-wide standardized test results, specifically reading and math scores of students to showcase obvious trends in school performance.

- Pandas and Jupyter notebook was used to write the code and create dataframes.

The final report includes the following:

### District Summary

A high-level snapshot, in a DataFrame, of the district's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary

A DataFrame that summarizes key metrics about each school, including the following:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Highest-Performing Schools (by % Overall Passing)

A DataFrame that highlights the top 5 performing schools based on % Overall Passing. Include the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)


### Lowest-Performing Schools (by % Overall Passing)

A DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Include the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Math Scores by Grade

A DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

A DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

A table that breaks down school performance based on average spending ranges (per student). Use your judgment to create four bins with reasonable cutoff values to group school spending. Include the following metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size

A table that breaks down school performance based on school size (small, medium, or large).

### Scores by School Type

A table that breaks down school performance based on type of school (district or charter).

### Analysis

* The dataset has a total of 15 schools and 39,170 students. The percent of students passing reading (85.80%) and their average reading score of 91.87 is higher than the percent of students passing math (74.98%) and their average math score of 78.98, which reveals that students are doing better in reading than math.

* The school summary shows that from the 15 schools, 7 district schools have more students than the 8 charter schools which can mean that the district schools’ geographical coverage can be a reason for their larger student population/ size.

* Based on the performance of spending ranges per student, students have a higher overall passing rate of 90.37 percent in the lower spending ranges (<$585).

* Small and medium sized schools performed better than large sized schools on passing math. There's 93.55 percent in small sized schools and 93.59 percent in medium sized schools passing math while there's only 69.96 percent in large sized schools passing math.

* The data shows that the Charter Schools are scoring better than the District Schools across all metrics (average, percent, and overall). Pena High School has the average math score (83.839917) with (94.59%) passing math and average reading score (84.044699) with (95.94%) passing reading while Huang High School has the average math score (76.629414) with (65.68%) passing math and average reading score (81.182722) with (81.31%) passing reading. Since Pena High School is a charter school with better scores and smaller student population while Huang High School is a district school with lower scores and larger student population, this can mean that schools with larger student population/ size negatively influences student achievements.
