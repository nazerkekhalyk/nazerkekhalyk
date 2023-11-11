CREATE TABLE STUDENTS (
studid INTEGER PRIMARY KEY,
name text not null,
course text not null
);
insert into STUDENTS VALUES (1, 'nazerke', '2');
SELECT * from STUDENTS where name = 'nazerke';
