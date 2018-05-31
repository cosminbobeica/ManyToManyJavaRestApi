# ManyToManyJavaRestApi

Java Spring Boot Rest Api + MySql Many To Many.
import the app and run as spring boot app
the application will generate in the mysql database(db) 3 students and 3 courses.

open browser-> acces  http://localhost:8080 and then you will see the HAL Browser.
-In the Explorer section type : /http://localhost:8080/student to see the stundets;
-In the "Embedded Resources" you will every student, click on one to see their name.
/http://localhost:8080/curs to see the courses.
/http://localhost:8080/student/1/cursuri to see all the courses for the first student.
/http://localhost:8080/curs/2/studenti to see all the students who are learning the second course.
