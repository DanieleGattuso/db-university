# db-university


1# SELECT * 
FROM students 
WHERE YEAR(date_of_birth) = 1990;


2# SELECT * FROM courses
WHERE cfu > 11

3# SELECT*
FROM students
WHERE timestampdiff(year,date_of_birth,CURDATE())>30
