# ICS3U Unit B Task

## Assignment Task
Your job is to create a Student Grade analyzer that will read student grades from a [CSV](https://docs.python.org/3/library/csv.html) and output a pretty table with a summary of each student's average, the whole class average, and the student with the highest and lowest grades

In this repository, you will see a compiled python file that is the solution to this problem. 

You will do this by creating a set of functions that implement this problem piece by piece

## Must Include
The functions you will define are as follows:

```python
# Return a list where each element is a list of the students' grades
read_csv(filename) 
# Returns the name of the student in the given row
get_name(s_grades) 
# Return the average of this student rounded to 2 decimal places
get_average(s_grades) 
# Returns the whole class average, rounded to two decimal places
calc_class_average(all_grades) 
# Returns the name and the average of the student with the highest class average 
get_student_highest_grade(all_grades) 
# Returns the name and the average of the student with the lowest class average 
get_student_lowest_grade(all_grades) 
# Print a nicely formatted table where each row contains the student's name and average
pretty_print(all_grades) 
# The main entry point for our program
main() 
```

# NOTE: For the pretty print. The rows only have two columns: the name and the average. Make the first column (the student's name) have a "width" of 25 characters and the second column (the student's grade) have a width of 5 characters.

You will also need to fill out the main_test.py file and write unit tests for the following functions:
```python
get_name(s_grades)
get_average(s_grades)
calc_class_average(all_grades)
get_student_highest_grade(all_grades)
get_student_lowest_grade(all_grades)
```

Also, make sure to include doc strings on all of your functions, even the ones you are not testing

## Grading
You will be marked on your solution (out of 4), coding style (out of 2), and comments (out of 2)

