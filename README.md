# LITA_Class_Documentation

### PROJECT TITLE: Data Cleaning, Analysis, Querying and Visualization using Microsoft Excel,SQL and PowerBI

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning](#data-cleaning)

[Exploratory Data Analysis](#exploratory-data-analysis)

### Project Overview
---
The primary aim of this project is to extract meaningful insights and knowledge from the raw data set using Excel for data entry and organization, data cleaning, perform data summarization, data visualization and insights using pivot tables, and conduct advanced querying for analysis using SQL by extracting, summarizing, combining, insering and updating.

### Data Sources
---
The data set was given by our tutors in persons of Mr Mushin and Mr Femi. Also, data was gotten from site such as kaggle

### Tools Used
---
- Microsoft Excel
1. For data cleaning
  i. Simple Arithmetic calculations [view](https://docs.google.com/spreadsheets/d/1dfztYuF8bpYCgHDVIgtoTa1yXnY-c14D/edit?gid=849939821#gid=849939821)

 ii. Data Validation(Removing Excess Spaces and Formatting of Text) [check](https://docs.google.com/spreadsheets/d/1vDIJYzXy4EPV8nN9usfVoX8brf01SOYZ/edit?gid=268669386#gid=268669386)
 
iii. Vlookup [view](https://docs.google.com/spreadsheets/d/13k_nWP8FeQZcpaEZffDgc16rO0sSgf1J/edit?gid=2120189425#gid=2120189425)

2. For analysis
   
 - Pivot Table for Report Summary
   
3. For visualization
   
   -Different Chart in Excel For Visualization
   
-SQL:Structured Query Language for Quering data and Data manipulation.It plays a vital role in data analysis, primarily because it allows users to interact with relational databases efficiently. 
```SQL
CREATE TABLE Employee (

staffid varchar (10) not null,

FirstName varchar (255) NOT NULL,

SecondName varchar (255),

Gender varchar (10),

Date_of_Birth date,

HireDate datetime,

primary key (staffid)

)

select * from Employee

insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth, hiredate)

values ( 'AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),

( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09'),

( 'AB223', 'joshua', 'chukwuemeka', 'male','1980-10-09', '2022-02-09'),

( 'AB234', 'sanni', 'ibrahim', 'male','1958-10-09', '2019-09-23'),

( 'AB254', 'mercy', 'olanipekun', 'female','1982-10-09', '2020-02-09'),

( 'AB249', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),

( 'AB298', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),

( 'AB260', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),

( 'AB281', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09')
```

-PowerBI: Power BI is a powerful data visualization and business intelligence tool that is primarily used in data analysis for the following purposes:

i. Data Visualization

ii. Data Connectivity and Integration

iii. Collaboration and Sharing

iv. Predictive Analytics

