# MyDiary_Project

Description
This Spring Boot Project is a diary application where users
can organize their thoughts and make them more
understandable. Users can login and can check their memories
even after a long period of time as it has been arranged in a
particuar date format.

step 1

Firstly I have created a spring
boot starter project with added
dependencies like data jpa, mysql
connector, tomcat jasper


step 2

Next I have created a database
named mydiary using mysql with
tables user and entry

step 3

Through application.propertiess I
made a connection to the
database. Through hybernate dta
jpa writes the queries by itself

step 4

Next I have created multiple layers
for controllers, repositories and
bussiness with required interfaces

step 5

Next I have created a controller with various method and annotations to
return jsp documents and execute the methods according to the /url

step 6

Next I have created jsp files in the WEB-INF folder and now the project is
ready to start


The server runs in the port 8080 by enterning localhost:8080/home
login page is visible and by entering /register registration page is visible


After Authentication if the user exists in the database you will be
loggined successfully else you will be landed in the error page



Through singout we will be return back to the login page
