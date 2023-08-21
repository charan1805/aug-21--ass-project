CREATE DATABASE School
use School
create table Student
(ID int,
Name nvarchar(50),
DateOfBirth date,
ClassId int )

 insert into Student (ID,Name,DateOfBirth,ClassId)values(1,'Sai','01/01/2001',101)
insert into Student (ID,Name,DateOfBirth,ClassId)values(2,'Sindhu','02/12/2003',102)
insert into Student (ID,Name,DateOfBirth,ClassId)values(3,'Kiran','05/12/2004',103)
insert into Student (ID,Name,DateOfBirth,ClassId)values(4,'Charan','09/12/2002',104)

create table Class
(
ID int,
Name varchar(10))
insert into Class values (1, 'Class8'), (2,'Class7'), (3,'Class6'), (4,'Class9'), (5,'Class10')

create table Subject(
ID int,
Name varchar(50))
insert into Subject values (1, 'Hindi'), (2,'Maths'), (3,'Physics'), (4,'Social'), (5,'Chemistry')
select * from Class
select * from Student
select * from Subject
update student set ID = 3 where name = 'Manuel'

