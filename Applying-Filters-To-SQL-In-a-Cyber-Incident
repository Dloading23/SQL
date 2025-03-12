# SQL
SQL Filtering Project

<h2>Description</h2>
This portfolio project varies from basic intro queries to more complex queries involving JOINS, OPERATORS, and FILTERING SQL queries to execute tasks for security incidents. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>MySQL</b> 

<h2>Environments Used </h2>

- <b>Khan Acdemny</b> (READ.ME Files)
- <b>DataCamp</b> 
- <b>Google Labs</b> 

<h2>Applying Filters to SQL Queries Explained:</h2>

<p align="center">
Project Scenario: We are investigating a recent security incident in this project.
We need to gather information about login attempts for certain dates and times. This will help in resolving the security incident.
First, we need to retrieve login events made after a certain date. Second, narrow the focus of the search to filter logins in a date range. Third, investigate logins that were made at certain times. Finally, filter login attempts based on their event IDs. <br/>


<h2>Retrieved after hours failed login attempts: <h2>
  <img src="https://i.imgur.com/Cd4XUb1.png">

  <h2>In this task, I am investigating a recent security incident for login attempts after work hours. To do this, I need to gather information about login attempts made after 18:00:00 time that were failed attempts.
   <br />
   <br />
Syntax: <br /> 
      SELECT *  FROM log_in_attempts <br />
        WHERE success = 0 AND  login_time > '18:00:00'; 
<br />
<br />
WHERE clause is filtering for 0 successful login attempts (in this case failed attempts), Then using the AND operator we filter for login times greater than 18:00:00.

<br />
<br />





Retrieved login attempts on specific dates:
<img src="https://i.imgur.com/x2GUz9W.png">
<br />
<br />
Syntax:  
SELECT * FROM log_in_attempts <br />
WHERE login_date <= '2022-05-09';
<br />
<br />
Explanation: 
In this task were investigating suspicious activity that occurred on 2022-05-09. We wanted to pull data that reviews all login attempts that occurred on this day and any attempts from the days before.The WHERE clause here filters for login_date for the dates on or before May 5th, 2022 for review of any suspicious activity 

Retrieved login attempts outside of Mexico: <br/>
<img src="https://i.imgur.com/YeI8L1v.png">
<br />
Syntax:
<br />
SELECT * FROM log_in_attempts <br />
WHERE country NOT LIKE 'MEX%' AND country NOT LIKE 'MEXICO%'; 
<br />
<br />
Explanation: <br />
In this Query our WHERE clause is filtering for countries that are NOT like Mexico instead it will only return results from the log_in_attempts table that are not Mexico in the country column, leaving only results from USA and Canada.<h2>
  
Retrieved employees in Marketing:  <br/>
<img src="https://i.imgur.com/TqEIU2K.png">
<br />
<br />
Syntax: <br />
SELECT *  FROM employees <br />
WHERE department LIKE '%Marketing%' AND office LIKE 'East-%'; 
<br />
<br />
Explanation: 
WHERE department LIKE '%Marketing%': <br />
    • Our WHERE filters for Matches of any value in the department column that includes the word "Marketing" anywhere in the text. 
    <br />
    <br />
AND office LIKE 'East-%': <br /> 
    • Matches any value in the office column that starts with "East-" (e.g., "East-170", "East-320").
<br />
<br />

Retrieved employees in Finance or Sales:
<img src="https://i.imgur.com/AzoJREU.png"/>
<br />
<br />
Syntax: <br />
SELECT *  FROM employees <br />
WHERE department LIKE '%Sales%' <br />
   OR department LIKE '%Finance%';
<br />
<br />

Retrieved all employees not in IT: <br/>
<img src="https://i.imgur.com/FdXr5Vl.png" height="80%" width="80%"/>
<br />
<br />
Syntax: <br />
SELECT * FROM employees <br />
WHERE department NOT LIKE '%Information Technology%'; <br />

Explanation:
   WHERE department NOT LIKE '%Information Technology%':
        ◦ The WHERE in this part of the query filters out any rows where the department column contains "Information Technology" to show a list of all employees related to the Information Technology department. <br />
        ◦ Matches all other departments.

Summary:  <br/>
The goal of this project was to utilize SQL querying skills to investigate a recent security incident by analyzing login data stored in a MariaDB database. The tasks involved extracting specific records based on criteria such as date, time, and event ID, leveraging various SQL operators and functions. Through this process, I showcased my proficiency in data filtering, handling date and time operations, executing range queries, and effectively managing real-world data scenarios relevant to a cybersecurity analyst's role.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
