#SQL

COMPANY :CODTECH IT SOLUTIONS

NAME:DIVYA DHARSHINI J

INTERN ID:CTO4DH1846

DOMAIN:SQL

DURATION:4WEEKS

MENTOR:NEELA SANTHOSH

In this task, I practiced different types of SQL JOIN operations using the Programiz SQL compiler, a simple online platform for running SQL queries. The main goal was to understand how JOINs work in combining data from two related tables.

I created two tables: Students and Marks. The Students table contained student IDs and names, while the Marks table included subject names and marks linked to some student IDs. The data was intentionally designed to include mismatches—for example, a student in the Students table with no marks, and a student in the Marks table who didn't exist in the Students table.

I started with an INNER JOIN, which only returned records where student IDs matched in both tables. This excluded unmatched entries like Charlie (no marks) and student ID 5 (no name).

Next, I used a LEFT JOIN to get all students, whether or not they had marks. For students without marks, the output showed NULL in the subject and marks columns. Then, with a RIGHT JOIN, I displayed all marks, including those without matching student names.

To simulate a FULL OUTER JOIN (not directly supported in all SQL systems), I combined the LEFT and RIGHT JOIN results using the UNION operator. This returned all students and all marks, matched or unmatched.

Overall, this task helped me clearly understand how JOINs behave with partial or mismatched data. The Programiz compiler made it easy to test and view the results instantly, helping me learn SQL more effectively.
