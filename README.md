# OptimalCourse-Planner-
We propose to design a student-friendly course planner that outputs an optimal schedule based on his/her preferences to graduate. The data used in our project is taken from the course list offered by CS department at UW-Madison (https://www.cs.wisc.edu/courses/list). We model the problem as a mixed-integer linear program (MILP). Though the objectives to graduate are different for every person, we assume that every student's objective falls into one of the following categories :

-Maximize grade point average
-Graduate by choosing courses of minimum difficulty
-Graduate by spending minimum tuition fees
-Graduate with maximum knowledge in his/her's area of interest

We propose to provide the optimal schedule based on the student's objective. The general problem setting is as follows:

Complete the number of credits needed to graduate.
Courses are numbered 200 through 900. Courses numbered 700 through 900 are core credit courses and the rest are non-core credits.
Every course is associated with a fixed number of credits. Credits vary from 1 to 6.
Courses are offered only in Spring or Fall semester or both.
The university demands that atleast 50 percent of the credits should be core credits.
