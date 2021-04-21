Quiz or Exam Management System
To Run Quiz or Exam Management System you need 2 external JAR file

1. MySQL JDBC Connector
To load MySQL Connector/J into your program you follow three steps below:

First, in NetBeans IDE, from project name Quiz or Exam Management System, right mouse click and choose properties menu item. The project properties dialog will appear.

Second, on the left hand side of the project properties dialog, from the Categories section, choose Libraries item.

Third, click on the Add JAR folder button, browse to the location where you find mysql-connector-java-8.0.20.jar, and choose the JAR file; after that click OK button.

2. rs2xml.jar
The rs2xml jar is used to display the data in a table format. So, once you create a project in Eclipse IDE, you have to import the rs2xml jar and JDBC connector JAR into the project.
right-click on the project, choose Build Path -> Configure Build Path. In the dialog box, which opens up, choose Add External JARs, and add the rs2xml.jar file. Once added, click on Apply and Close.


Steps to connect to our database

Step 1. Open MySQL Workbench.
Step 2. Click New Connection towards the bottom left of MySQL Workbench.
Step 3. In the “Set up a New Connection Dialogue” box, Type your Database connection credentials. The credentials will be like the following:

Connection Name: QEMS
Connection Method: Standard (TCP/IP).
Hostname: 127.0.0.1
Port: 3306
Username: root
Password: 31122002

Click Test Connection.

Create Database

Step 1: create database qems;

Step 2: Open qems.sql and run all the commands

Step 3: qems.sql will create 2 tables called student and question 
it will also insert values in both the tables.

