# 31-03-2023

## Answers
### 1. What is File System?
   -File System is a traditional way of storing data in a local server.
   -File System stores data in Hierarchical Manner.
   -In File System there is a possibility of Data Redundancy(Repeatation of Data).
   -File System comes with the OS of the Device.

### 2. What is database?
   -Database is an organised way of storing related data.
   -Mostly database uses tables to store the data in an organised manner.
   -updating,retrieving and deleting of data in achieved efficiently.

### 3. Why we need to use database instead of File System?or What are the advantages of database?
   
   -No redundancy(reputation of data).
   -Data stored is related.
   -We can store large amount of Data
   -Fetching and updating is easier
   -More Secured
   -accurate information compared with File system.
   -Readability is good as data is stored in the form of Tables.

### 4. What is DBMS?
   -DBMS stands for Database Management System
   -It is a software acts as communicator between database and the user
   -It helps us to insert,update,retrieve and delete data from the database

### 5. What is
   1. DML?
      -DML stands for Data Manipulation Language
      -DML commands are used to manipulate the tables of the database
      -There are mainly Three DML operations tey are :
      A.Insert B.Update and C.Delete

   2. DDL?
      -DDL stands for Data Definition Language
      -DDL commands are deals with Structure of the Table
      -DDL Commands are:
      A.Create B.Alter C.Drop and C.Truncate


### 6. What are popular databases?
   Popular Databases are MySQL,Oracle SQL,MS SQL,MangoDB,PostgresSQL


### 7. Which companies built above listed databases?
   -MySQL -> Developed managed by Oracle
   -Oracle SQL ->Developed managed by Oracle
   -MS SQL -> Developed managed by Microsoft
   -MangoDB -> MongoDB Inc.
   -PostgresSQL -> PostgresSQL Global Development Group


### 8. Write a query to create Person table with below attributes
   1. Id
   2. Name
   3. DOB
   4. Email
   5. Phone Number
   6. Address (string)
   #Query
      1.create database PersonData
      2.use database PersonData
      3.create table PersonDetails(
      Id int,
      Name varchar(20),
      DOB date,
      Email varchar(30),
      PhoneNumber int,
      Address varchar(100));


### 9. Write a simple query to fetch person with given id
   use PersonData
   select Id from PersonDetails
   where Id = xyz;


### 10. Write a simple query to fetch person with given name and email

    select * from PersonDetails
    where Name = "saicharan" and Email ="saicharan@gmail";

### 11. Write a simple query to fetch person with email not equals to
    "abc@gmail.com" and "xyz@gmail.com"

    select * from PersonDetails
    where Email not in("abc@gmail.com","xyz@gmail.com");


### 12. Write what else you know about DBMS and SQL.
    -SQL standeds for Structured Query Language.
    -We use SQL Queries for manupulating the data in the relational databases.


