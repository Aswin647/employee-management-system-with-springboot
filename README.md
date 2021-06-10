# employee-management-system-with-springboot

PROJECT NAME: EMPLOYEE MANAGEMENT SYSTEM( REST API CRUD PROJECTS)

DESCRIPTION: This is the project name employee management system developed by me featuring the basic CRUD implementation. In this project we can get all the list of cutomer as well as we can get the customer by one by one by its id as well as we can add , update and delete the customer.

SERVER USE: TOMCAT, apache

BRIEF OF CODE: Inorder to develop this this project, the dependencies and project server  is created and downloaded from the "spring.initializer.i.o" in maven. this is the REST API CRUD projects which endpoints is passed into postman and checked successfully .
As much as to talk about the code there is RESTcontroller package where all the bussiness logic is written as well as there is DAO,S packags for accessing the data from the database and there is SERVICES PACKAGes which connect or access to the DAO and there is one entity class which should be named same of table created in SQL.

NOTE: (1) in this project there is two dao,s implementation technique one with the hibernate api and other with the JPA api, u can use one dao techniques by using the
annotation @qualifier on service implementation class..

         (2) the other thing   is that you can also use 'SPRING DATA JPA  dao techniques  [ in which there is no need of   DAO and dao implementation class and all you need to do is extend the JPA repository]  and SPRING REST DATA  dao techniques [ in which dao class and services both classes are not required as well as controller packages is also not needed , all you need to do is extend the jpa repository and add the dependency of spring DATA REST in POM.XML file.].


