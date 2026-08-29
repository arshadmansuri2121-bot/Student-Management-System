Student Management System — MySQL Project

A relational database project built for SQL practice, modeling a college's students, courses, departments, faculty, and enrollments, with a set of analytical queries run in MySQL Workbench.

Overview
Entity	Records
Students	500
Courses	6
Departments	3
Faculty	30
Enrollments	1,933

Database: MySQL Tool used: MySQL Workbench

Schema

The database consists of five related tables:

students — student records, each linked to a course
courses — course catalog, each linked to a department
departments — department records
faculty — faculty records
enrollments — links students to courses with total_marks, enabling performance analysis
SQL Concepts Demonstrated
INNER JOIN / LEFT JOIN
GROUP BY with aggregate functions (COUNT, AVG, MAX)
Correlated subqueries
ORDER BY and LIMIT
Conclusion

The Student Management System successfully connects students, courses, departments, faculty, and enrollments, and the queries above demonstrate how relational SQL can be used to analyze student distribution, course enrollment, and academic performance. The schema can be extended further with modules for attendance, fees, and examinations.

Author

Arshad Mansuri — IT Vedant, SQL / MySQL Project.
