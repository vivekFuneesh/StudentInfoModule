# StudentInfoModule
A simple form processing in springboot through .jsp page. Database is mongodb.

            Under GPLv3

add, update, delete and retrieve student info.
add: have to fill all details.
update: have to fill all details.
delete: can be deleted by rollno only.
retrieve: get list of all students in different lines.

constraints: 
joiningYear>2000 && joiningYear<current_Year 
age>0 and age<100
name != blank or null
rollno != blank or null
standard can be any string.

edit pom.properties file.
database name can be changed in UriInitializer.java
no username and password for mongodb.
