# Spring Boot students handler Web application

Simple overview of use/purpose.

## Description

Spring Boot 2.7.5, MVC, Thymeleaf, JPA

## Getting Started

### Dependencies

* Java 11
* PostgreSQL

### Installing
* Create "student_management" database
* Create "student-management-1.0.0.jar"
```
sudo update-alternatives --config java (select Java 11)
gradle clean bootjar
```

### Executing program

* Run "student management" application
```
java -jar student-management-1.0.0.jar
```
* List students
```
http://localhost:8088/students
```
* Add new student
```
http://localhost:8088/students/create
```

## Author

Kenyeres Géza
https://hu.linkedin.com/in/g%C3%A9za-kenyeres-17341631

