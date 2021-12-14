# Taxi-service
___
#### This is a prototype of a web application for a taxi service. Here, the users are the drivers of our service. By registering a new driver and logging into the system, you will be able to:
* Add new and delete old cars and manufacturers
* Register new drivers
* Track all cars, drivers and manufacturers of our service
* Track your cars as a driver
* Link existing cars to your driver

## Project structure

#### The structure of this project consists of 3 levels:
* Data access layer (DAO)
* Application layer (service)
* Presentation layer (controllers)

## Technologies that were used

#### Database technologies:
* MySQL
* JDBC

#### Web technologies:
* Apache Tomcat
* Servlet
* JSP
* JSTL
* HTML, CSS

## How to start the application

1. Install and configure Apache Tomcat(v9.0.50)
2. Install MySQL with Workbench
3. Use the script from resources/init_db.sql to create a database with the required tables
4. In the util / ConnectionUtil.java class, enter your database data in the fields instead of stubs
5. Also in the log4j.xml file, instead of a stub (fileName = "YOUR PATH"), enter the absolute path to the file in which you want to write logs
6. Run the app
