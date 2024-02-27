# student_result_management_system 

# admin credintials are in given below table. So please use following credintials to login to admin section.
+----------+----------+
| username | password |
+----------+----------+
| admin1   | pass1    |
| admin2   | pass2    |
| admin3   | pass3    |
| admin4   | pass4    |
| admin5   | pass5    |
+----------+----------+

In this project I have implemented different fuctionalities for admin section like adding a new student,adding existing student results, readiing the registered students and reading results of all students adn for student section I have added fuctionality for viewing all details

Coming to database, I have implemented following tables

# Table Name : admin
+----------+-------------+------+-----+---------+-------+
| Field    | Type        | Null | Key | Default | Extra |
+----------+-------------+------+-----+---------+-------+
| username | varchar(15) | YES  |     | NULL    |       |
| password | varchar(15) | YES  |     | NULL    |       |
+----------+-------------+------+-----+---------+-------+

# Table Name : student
+-------------+-------------+------+-----+---------+-------+
| Field       | Type        | Null | Key | Default | Extra |
+-------------+-------------+------+-----+---------+-------+
| rollno      | varchar(15) | NO   | PRI | NULL    |       |
| course      | varchar(15) | YES  |     | NULL    |       |
| branch_name | varchar(15) | YES  |     | NULL    |       |
| name        | varchar(20) | YES  |     | NULL    |       |
| gender      | varchar(15) | YES  |     | NULL    |       |
| father_name | varchar(20) | YES  |     | NULL    |       |
+-------------+-------------+------+-----+---------+-------+

# Table Name : result
+---------+-------------+------+-----+---------+-------+
| Field   | Type        | Null | Key | Default | Extra |
+---------+-------------+------+-----+---------+-------+
| rollno  | varchar(15) | NO   | PRI | NULL    |       |
| maths   | varchar(15) | YES  |     | NULL    |       |
| physics | varchar(15) | YES  |     | NULL    |       |
| dbms    | varchar(15) | YES  |     | NULL    |       |
| os      | varchar(15) | YES  |     | NULL    |       |
| cn      | varchar(15) | YES  |     | NULL    |       |
+---------+-------------+------+-----+---------+-------+
